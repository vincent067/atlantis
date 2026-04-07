FROM gcr.io/oss-fuzz-base/base-builder-go@sha256:654b6ffa343d1e1d5222ca0144ecdb4bfb09487e545c82571a77211f1b0e425c
COPY . $SRC/atlantis
COPY .clusterfuzzlite/build.sh $SRC/build.sh
WORKDIR $SRC/atlantis
