# MaryTTS Docker image for Sorbian languages

## Prerequisites

Docker must be installed.

## Building the image

Run

    docker buildx build -t marytts/marytts-dsb-hsb . \
        --platform linux/arm64/v8,linux/amd64 --push

## Running the container

Run

    docker run -it --rm -p 59125:59125 marytts-hsb-dsb

Then access MaryTTS via browser on the host at <http://localhost:59125>.
