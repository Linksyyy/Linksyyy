<h1 align="center">Adriel ♜</h1>
<p align="center">Computer Science @ UFS · Aspiring software engineer · Chaos Architect</p>

<div align="center">
  <h3>Main Stack:</h3>
  <img src="https://skillicons.dev/icons?i=cpp,js,ts,nodejs,deno,bun,html,css,postgres,mysql,mongodb" alt="Main Tech Stack" /><br><br>
  
  <h3>Others:</h3>
  <img src="https://skillicons.dev/icons?i=arch,emacs,vscode,vim,visualstudio" alt="Other Tech Stack" />
</div>

---

### ♝ Tech I'm fluent in:
> `C++` · `JavaScript` · `TypeScript` · `Python`  
> `Node.js` · `Deno` · `HTML/CSS` · `PostgreSQL`

### ♞ About me:
- Computer Science student @ UFS (🇧🇷)
- Obsessive about performance, clean architecture & low-level thinking
- Always tweaking, profiling, and over-optimizing (for fun)
---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Linksyyy&theme=midnight-purple&show_icons=true&hide_border=true&count_private=true">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Linksyyy&theme=midnight-purple&show_icons=true&hide_border=true&layout=compact">
</p>

---

\documentclass{article}
\usepackage[margin=0.25in]{geometry}
\usepackage{pgfplots}
\pgfplotsset{width=10cm,compat=1.9}

% We will externalize the figures
\usepgfplotslibrary{external}
\tikzexternalize

\begin{document}

First example is 2D and 3D math expressions plotted side-by-side.

%Here begins the 2D plot
\begin{tikzpicture}
\begin{axis}
\addplot[color=red]{exp(x)};
\end{axis}
\end{tikzpicture}
%Here ends the 2D plot
\hskip 5pt
%Here begins the 3D plot
\begin{tikzpicture}
\begin{axis}
\addplot3[
    surf,
]
{exp(-x^2-y^2)*x};
\end{axis}
\end{tikzpicture}
%Here ends the 3D plot

\end{document}
