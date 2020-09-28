# Tableau-Public
This repository contains scripts used to create the [VOTD colour analysis dashboard](https://public.tableau.com/profile/luisa6565#!/vizhome/VOTDColourAnalysis/Dashboard1).

- **VOTD.ipynb** scrapes all VOTDs including title, date and thumbnail.

- **Dominant colour.ipynb** is based on https://github.com/aysebilgegunduz/DominantColor and analyses the dominant colour in each VOTD thumbnail. It outputs the RGB codes to a DataFrame.

- **Top 3 colours by number of pixels.ipynb** counts the number of pixels with a specific RGB code in an image. It wasn't used in this project because JPEG compression mean that results would be skewed.

## Results

Unsurprisingly, white colours have been used as most dominant colours for most visualisations which can be attributed to the background colour. It is followed by other neutral colours such as grey and black.

A visualisation of the results can be found [here](https://public.tableau.com/profile/luisa6565#!/vizhome/VOTDColourAnalysis/Dashboard1).

![image](https://user-images.githubusercontent.com/59416844/83361265-69d59300-a37f-11ea-82b8-07e2e22a9ecd.png)
