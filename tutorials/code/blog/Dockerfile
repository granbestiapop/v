FROM vlang:alpine

WORKDIR /app

## Add all sources
COPY * /app/

## Compile
RUN v blog.v

## Run
CMD [ "./blog" ]