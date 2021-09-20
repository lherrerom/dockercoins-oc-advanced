# dockercoins

git clone https://github.com/academiaonline/dockercoins

git checkout 2021-09

for app in hasher rng webui worker
do
  docker image build --file Dockerfile-${app} --tag academiaonline/dockercoins:2021-09-${app} /mnt/
done

