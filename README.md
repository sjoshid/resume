### Quick start

* Go to [Overleaf](https://www.overleaf.com/) and login.
* Copy/paste .tex file located at root of the project. 
* Enjoy. 

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sourabh_bajaj_resume.tex
```

### Preview

![Resume Screenshot](/resume_preview.png)

### License

Format is MIT but all the data is owned by Sourabh Bajaj.
