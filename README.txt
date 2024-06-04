The schemas have been obtained by running the following bash script and massaging the results a bit.

for i in {0..2000}; do echo "Downloading $i"; curl -OJ "https://www.iso20022.org/message-set/$i/download"; done
