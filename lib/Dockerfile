FROM quay.io/hermit/hermit-ser:latest

RUN git clone https://github.com/hil3m/hilem-md /root/hilem-md
WORKDIR /root/hilem-md/
RUN yarn install --network-concurrency 1
CMD ["node", "index.js", "--max_old_space_size=2560"]
