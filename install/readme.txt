----------> INSTALLATION

npm install pug

----------> PATH TO index.html

pug -w ./ -o ./html -P

----------> IF “permission denied /usr/lib/node_modules” Code Answer

sudo chown -R $(whoami) ~/.npm

mkdir ~/.npm-global
npm config set prefix '~/.npm-global'
export PATH=~/.npm-global/bin:$PATH
source ~/.profile

---------->