# Figure sources

Original Figure 1 images from the authors' arXiv papers, downloaded on 2026-11-21. Previews show the complete figures and link to full-size local images.

| Local file | Source |
| --- | --- |
| collective-experience-learning-fig1.png | https://arxiv.org/html/2610.25736v3/overview.png |
| rlinf-user-fig1.png | https://arxiv.org/html/2602.07837v6/figures/sys-arch.png |
| rlinf-vla-fig1.png | https://arxiv.org/html/2510.06710v3/from-twh-rlinf_vla_overview_new.png |
| online-ggo-fig1.png | https://arxiv.org/pdf/2411.16506v2, page 1, Figure 1 |
| uav-formation-fig1.png | https://arxiv.org/html/2410.18495v2/crop_overview.png |

Online GGO is rendered from the PDF using Poppler at 450 dpi, cropping only surrounding page text. It includes the original shared colorbar, all three heatmaps, and their subfigure labels. Command:
    
    pdftoppm -f 1 -singlefile -r 450 -x 2016 -y 1434 -W 1470 -H 450 -png online-ggo.pdf online-ggo-fig1

The Open Source logo at ../rlinf-logo.svg is the unmodified official asset from https://raw.githubusercontent.com/RLinf/misc/main/pic/logo_white.svg.
