# RenderCV YAML Example: Le Minh Tam

This repository contains the YAML and supporting files for generating a professional CV using [RenderCV](https://rendercv.com).

## Example Usage

### 1. Install RenderCV
If you haven't already, install RenderCV (full version recommended):

```sh
pip install "rendercv[full]"
```

### 2. Create a New CV Template (Optional)
To create a new RenderCV template, run:

```sh
rendercv new "Your Full Name"
```

### 3. Render the CV
From your project directory, run:

```sh
rendercv render CV.yaml
```

#### Tip: Auto-Render on Save
To have RenderCV run automatically whenever the YAML input file is updated, use the `--watch` option:

```sh
rendercv render --watch "Your_Name_CV.yaml"
```

This will generate PDF, PNG, and HTML versions of your CV in the output directory (default: `rendercv_output`).

### 3. Output Files
- PDF: `rendercv_output/CV.pdf`
- PNG: `rendercv_output/CV.png`
- HTML: `rendercv_output/CV.html`

## Customization
- Edit `CV.yaml` to update your personal information, skills, education, experience, and projects.
- See [RenderCV documentation](https://docs.rendercv.com/) for advanced formatting and section options.

## License
This project is for personal use. See RenderCV's [license](https://github.com/rendercv/rendercv/blob/main/LICENSE) for tool usage terms.
