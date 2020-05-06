# h5ai Dark Theme
A simple style addition to h5ai to convert the whole white interfance into a dark themed UI.

## Getting started

### Prerequisites

- [h5ai](https://larsjung.de/h5ai/) must be installed and working.

### Installation

- Go to h5ai's CSS folder : `cd _h5ai/public/css`
- Backup the existing CSS file : `cp styles.css styles.css.bak`
- Download the minidifed dark CSS here : `wget https://raw.githubusercontent.com/RafaelDeJongh/h5ai-dark-theme/master/dark-theme.min.css`
- Copy the contents of the dark CSS file into the original CSS file : `cat dark-theme.min.css >> styles.css`
- *(optional)* Delete the dark CSS file : `rm dark-theme.min.css`

If you ever need to restore the original CSS file, just replace the active one with the backup : `mv styles.css.bak styles.css`

![Dark Theme](https://camo.githubusercontent.com/21fdbe4de166a2c98401150193540ecd830e79e1/68747470733a2f2f692e696d6775722e636f6d2f316378396d7a432e706e67)
