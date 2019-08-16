# Template for reproducible R projects

## Dependencies

 - docker

## Usage

Run the following:

```
docker build --tag=my-test-image .
docker run --rm -d --name=my-test-container -p 8787:8787 my-test-image
```
Then run RStudio from within your browser by navigating to `http://localhost:8787`

> Inspired by Cole Arendt's post: [Package Management for Reproducible R Code](https://rviews.rstudio.com/2018/01/18/package-management-for-reproducible-r-code/)
