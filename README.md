# Gnumeric_docker
Convert spreadsheet files using Gnumeric ssconvert tool

# Usage

    docker run -u $(id -u):$(id -g) -v /PATH_TO_FOLDER_WITH_FILE/:/home/user spoonest/gnumeric_docker ssconvert sample.xlsx sample.csv
