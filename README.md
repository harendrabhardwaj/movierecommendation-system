# Movie Recommender System
### Sooftware and Tools Requirements
1. [GithubAccount](https://github.com/)
2. [HerokuAccount](https://id.heroku.com/login)
3. [VSCodeIDE](https://code.visualstudio.com/download)
4. [GITCLI](https://git-scm.com/downloads)
5. [TMDB](https://www.themoviedb.org/)
6. [TMDBAPI](https://developers.themoviedb.org/3SSSS)
7. [Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

Create a new Environment:--
```
conda create -p venv python==3.7 -y
conda activate [Path] venv

Now to deploy on heroku platform we need to create a proc file.
Proc------>This file require specifies commands which needs to be executed by the app as soon as it starts.

While running the model this will create 2 pickle file similarity.pkl and movies.pkl, which is use in our app to processing the data.
```
