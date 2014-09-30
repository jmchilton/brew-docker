# Homebrew Docker Containers for Bioinformatics

cd base
docker build --tag="jmchilton/brew-base" .
cd ../java
docker build --tag="jmchilton/brew-java" .
