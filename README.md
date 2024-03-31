# UBC presentation template

 A UBC LaTex presentation template. The theme is based on `rectangles beamer`. All colours and logos are from [UBC Brand](https://brand.ubc.ca/guidelines/downloads/). Colours and logos are updated as of 30-March-2024.

 ## Install instuctions

1. Copy [`beamerthemeubc.sty`](/beamerthemeubc.sty) and [`ubccolours.sty`](/ubccolours.sty) and the [`logos` directory](/logos) to the main project directory.

2. Set document class to `beamer`, the theme to `ubc` and add the title graphic and logo.

    ```{=latex}
    \documentclass{beamer}
    \usetheme{ubc}

    \titlegraphic{\includegraphics[width=0.7\textwidth]{logos/ubc_logo_full_blue.png}}
    \logo{\includegraphics[height=0.15\paperheight]{logos/ubc_crest_white.png}}
    ```

3. (Optional) For a working example, see [`ubc_presentation.tex`](/ubc_presentation.tex).

