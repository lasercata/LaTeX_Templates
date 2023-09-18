# LaTeX Templates
This repository contain my LaTeX template, as well as some examples of drawings.

## Usage
First download the template :
```bash
git clone https://github.com/lasercata/latex_templates
```

Then :
```bash
mkdir ~/Templates
ln -s path/to/repo/0.Templates/latex_base.sty ~/Templates/latex_base.sty
ln -s path/to/repo/0.Templates/latex_base.tex ~/Templates/latex_base.tex
```

Use absolute path when creating the symbolic links.

And when creating a new tex file :
```bash
#cd to your project, and then do
cp ~/Templates/latex_base.tex file_name.tex

nvim file_name.tex #Or use any other editor
```

On some editors you can also directly add the `latex_base.tex` file as a templates.
