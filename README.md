# Zicheng Zhu's personal website

This repository contains the complete published website at [www.zicheng-zhu.com](https://www.zicheng-zhu.com/). GitHub Pages serves the files in the repository root from the `main` branch.

## Continue on another computer

```sh
git clone https://github.com/zichengzhu/zichengzhu.github.io.git
cd zichengzhu.github.io
python3 -m http.server 8765
```

Open <http://localhost:8765/> to preview changes. Edit the HTML, CSS, JavaScript, and files in `assets/`, then commit and push to `main` to update the live site.

`cv.html` is the web CV. `Zicheng-Zhu-CV.pdf` is the downloadable version; regenerate and replace it whenever the CV content changes. Keep the `CNAME` file so the custom domain continues to work.
