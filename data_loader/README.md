# RHC Load accounts example

**Docker build:**
docker build -t data_loader data_loader/.

**Docker run:**
docker run --rm -v /*repository path*/rhc-load-accounts-example/data.zip:/tmp/data/data.zip:ro -it data_loader

data.zip can be made from the sample data in the data folder. Just compress ammo, answers, data into data.zip archive and it will be ok.
