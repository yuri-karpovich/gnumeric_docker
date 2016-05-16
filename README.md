# Gnumeric_docker
Convert spreadsheet files using Gnumeric ssconvert tool

# Usage

    docker run -u $(id -u):$(id -g) -v /PATH_FO_FOLDER_WITH_FILE/:/home/user gnumeric ssconvert sample.xlsx sample.csv