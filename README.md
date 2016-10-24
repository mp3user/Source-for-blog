## Tuts+ Premium Series "Cheap and Scalable Websites With Flask and S3"

This repository holds the code for the Tuts+ Premium screencast series "Cheap and Scalable Websites With Flask and S3". The `master` branch holds the code in it's final form, i.e., as it was at the end of the last episode of the series. Tags have also been added to allow you to checkout the source as it was at the end of a particular episode.

### Setup

1. Get the [source code][source] for the course

        % git clone https://github.com/croach/cheap-and-scalable-websites-code.git

2. Create a virtual environment for the course and install the required software found in the requirements.txt file.

        % mkvirtualenv cheap-and-scalable-websites
        % cd /location/of/cloned/repository
        % pip install -r requirements.txt

3. (optional) Set the cloned repository as the project directory.

        % setvirtualenvproject       # you must be in the cloned repository

4. (optional) Checkout the source for a specific episode 

        % git tag                    # list all tags (one per episode)
        % git checkout <tag>         # branches are by course, tags by episode

5. Run it

        % python generator.py        # this will start up the development server


[source]: https://github.com/croach/cheap-and-scalable-websites-code/archive/master.zip
# mp3user.github.com
