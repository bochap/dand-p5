# Ford GoBike System Data Usage Patterns
## by Darren Seet

## Dataset

> This data set contains anonymized trip data from the Bay Wheels bicycle sharing service operated by Bay Area Motivate, LLC ("Motivate"). Motivate is an organization that is committed to supporting bicycling as an alternative transportation option. The organization operates multiple bicycle sharing service progams. This dataset contains the data from the Ford GoBike program which is the second largest bike share program in the US with 7,000 bikes, serving San Francisco, San Jose and the East Bay. The dataset contains data for the full year of 2018, 2019 and partial data in 2017, 2020.

## Summary of Findings

> * Peak hours in Weekdays (7:00 - 9:00 and 16:00 - 19:00) display a high amount of usage 
> * Customer user types also uses the system during the day time on the Weekends.
> * Customer user types tend to make trips with longer durations.
> * Usage patterns appear to be very consistent across 2018 and 2019 except for durations
> * 2018 usage durations tend to be longer although 2019 has higher usage counts.

## Directory Structure

This is the folder structure of the project

```bash
.
├── LICENSE
├── dand.yml                              ' Conda environment file
├── ford-go-bike-explanation.html         ' Exported file for explanation
├── ford-go-bike-explanation.ipynb        ' Code file for explanation
├── ford-go-bike-explanation.slides.html  ' Exported slides file for explanation
├── ford-go-bike-exploration.html         ' Exported file for exploration
├── ford-go-bike-exploration.ipynb        ' Code file for exploration
├── output_toggle.tpl                     ' Template file for presentation export
└── readme.md                             ' This file for project description
```

## Setup

### Prerequisites

1. Python setup on the host
2. conda setup on the host
3. conda environment that is similar to dand.yml

### Running locally

1. Clone repository by running `git@github.com:seetdev/dand-p5.git`
2. Go into the cloned folder
3. Create conda environment `conda env create -f dand.yml`
4. Run the notebook using `jupyter notebook`
5. Run all cells in `ford-go-bike-explanation.ipynb`
6. Run all cells in `ford-go-bike-exploration.ipynb`