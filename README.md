# docker-debian-node-chromium

## Usage

docker run --volume your_source_path:/var/www --workdir /var/www --rm jbcisne/debian-node-chromium node node_modules/@angular/cli/bin/ng test --codeCoverage=true --watch=false --sourcemaps=true