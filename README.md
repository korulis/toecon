# toecon

It is about taccon and ticcon deployment.

- __Clone this repo using `git clone --recurse-submodules git@github.com:korulis/toecon.git`__
- This repo has [submodules](https://git-scm.com/book/en/v2/Git-Tools-Submodules)
- It has reference to [ticcon](https://github.com/korulis/ticcon) react app
- It has reference to [taccon](https://github.com/korulis/taccon) flask web api
- Run the whole cluster `docker-compose up --build`
- Find the app at `http://localhost:4000/`
- Can use env var `TACCON_API_TEST_DELAY` (in secconds) to play with backend response delays
