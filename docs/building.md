# Build from source TL;DR

0. Install Go

1. Get the source 

        $ go get -u -d github.com/GoogleCloudPlatform/skaffold
    
1. Build and install Skaffold to `$GOPATH/bin/skaffold`

        make install 

    skaffold vendors all of its dependencies so make install should work out of the box

