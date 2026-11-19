# Learning and Accessibility Tools

This repository explores ideas and tools for creating more accessible research and educational material in collaboration with AI.

A video tutorial demonstrates this approach: it was created with Claude using PowerPoint slides and speaker notes, with narration and subtitles in English, German and Romanian.

**Explore the example and resources on the landing page:** [https://ducspe.github.io/learning-and-accessibility-tools/](https://ducspe.github.io/learning-and-accessibility-tools/)

## References

1. [Video tutorials and slides](https://ducspe.github.io/DCPresentations/)
2. [Weights & Biases](https://wandb.ai)
3. [Vega-Lite](https://vega.github.io/vega-lite/)
4. [smalldiffusion](https://github.com/yuanchenyang/smalldiffusion)
5. [Manim](https://github.com/3b1b/manim)
6. Piper: [TTS engine](https://github.com/OHF-Voice/piper1-gpl) | [Voice models](https://huggingface.co/rhasspy/piper-voices)
7. [ElevenLabs](https://elevenlabs.io/)

## Backup

If GitHub Pages is slow or unavailable, access the video tutorials in the [Google Drive backup folder](https://drive.google.com/drive/folders/1vXS13uBE1TEwNyySQcSmUgNsimBlhYFX?usp=sharing).

## Prism workaround: LaTeX in VS Code

[OpenAI Prism will shut down on January 1, 2027](https://openai.com/index/introducing-prism/). Export your Prism projects before that date to keep your files. A close alternative for writing, compiling, and previewing LaTeX locally is **VS Code + TeX Live + LaTeX Workshop**. Add the [Codex extension by OpenAI](https://marketplace.visualstudio.com/items?itemName=openai.chatgpt) for AI assistance with drafting, revising, and fixing LaTeX errors.

### Install the tools

1. Install [TeX Live](https://tug.org/texlive/quickinstall.html). It supplies the LaTeX compilers, packages, fonts, and the `latexmk` build tool. On Windows, you can install without administrator rights by running the installer normally and choosing a writable folder under your user profile, such as `%LOCALAPPDATA%\texlive\2026`. Allow the installer to add its binaries to your user PATH.
2. In [VS Code](https://code.visualstudio.com/), open Extensions with **Ctrl+Shift+X**, search for **LaTeX Workshop** by **James Yu**, and click **Install**. You can also open its [Marketplace page](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop). Clicking Install is enough; no extension-installation command is needed.
3. Fully restart VS Code so that it can find TeX Live. Optionally check the installation in a new VS Code terminal:

   ```powershell
   pdflatex --version
   latexmk --version
   ```

### Create and build a project

Create a folder for your document and open it using **File > Open Folder** in VS Code. Create a file named `main.tex` with this minimal example:

```latex
\documentclass{article}
\begin{document}
Hello from VS Code!
\end{document}
```

For an existing project exported from Prism, extract the project files into a folder, open that folder in VS Code, and open its main `.tex` file instead.

Save the file, then open a terminal in the project folder and run:

```powershell
latexmk -pdf -synctex=1 -interaction=nonstopmode -file-line-error main.tex
```

This builds `main.pdf`. The `latexmk` command manages the compilation passes needed to generate the PDF; the project itself is the folder containing your `.tex` files, figures, and bibliography. Replace `main.tex` in the command if your main file has another name.

### Build and see changes in the PDF

With the main `.tex` file active in VS Code:

- **Ctrl+Alt+B** builds the project using LaTeX Workshop's default `latexmk` recipe. This is the editor shortcut for building, so you do not need to repeat the terminal command.
- **Ctrl+Alt+V** opens the PDF preview inside VS Code. Keep it beside the source to see your document as you work.
- After each successful build, the open PDF preview **refreshes automatically** to show your changes.

For automatic rebuilding whenever you save, create or update `.vscode/settings.json` in your document's project folder with these settings (merge them with any existing settings):

```json
{
  "latex-workshop.latex.autoBuild.run": "onSave",
  "latex-workshop.view.pdf.viewer": "tab",
  "latex-workshop.synctex.afterBuild.enabled": true
}
```

Now edit the text and press **Ctrl+S**: LaTeX Workshop rebuilds the document, refreshes the PDF when compilation succeeds, and moves the preview to the source cursor's location. Changes appear after compilation finishes. You can still use **Ctrl+Alt+B** to build manually.

See the LaTeX Workshop guides for [building projects](https://github.com/James-Yu/LaTeX-Workshop/wiki/Compile) and [PDF preview and source navigation](https://github.com/James-Yu/LaTeX-Workshop/wiki/View).
