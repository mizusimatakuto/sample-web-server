# sample-web-server
テクノロジー（藤原）Node.jsによるサンプルWebサーバ

```

[{"breeds":[{"weight":{"imperial":"6 - 12","metric":"3 - 5"},"id":"bure","name":"Burmese","cfa_url":"http://cfa.org/Breeds/BreedsAB/Burmese.aspx","vetstreet_url":"http://www.vetstreet.com/cats/burmese","vcahospitals_url":"https://vcahospitals.com/know-your-pet/cat-breeds/burmese","temperament":"Curious, Intelligent, Gentle, Social, Interactive, Playful, Lively","origin":"Burma","country_codes":"MM","country_code":"MM","description":"Burmese love being with people, playing with them, and keeping them entertained. They crave close physical contact and abhor an empty lap. They will follow their humans from room to room, and sleep in bed with them, preferably under the covers, cuddled as close as possible. At play, they will turn around to see if their human is watching and being entertained by their crazy antics.","life_span":"15 - 16","indoor":0,"lap":1,"alt_names":"","adaptability":5,"affection_level":5,"child_friendly":4,"dog_friendly":5,"energy_level":4,"grooming":1,"health_issues":3,"intelligence":5,"shedding_level":3,"social_needs":5,"stranger_friendly":5,"vocalisation":5,"experimental":0,"hairless":0,"natural":0,"rare":0,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/Burmese_(cat)","hypoallergenic":1}],"id":"hj7Oh-SRY","url":"https://cdn2.thecatapi.com/ima

takuto@DESKTOP-8UMKL44:~$ cd hujiawra
-bash: cd: hujiawra: No such file or directory
takuto@DESKTOP-8UMKL44:~$ cd hujiwara
-bash: cd: hujiwara: No such file or directory
takuto@DESKTOP-8UMKL44:~$ cd fujiwara
takuto@DESKTOP-8UMKL44:~/fujiwara$ git clone git@github.com:mizusimatakuto/sample-web-server.git
Cloning into 'sample-web-server'...
remote: Enumerating objects: 7, done.
remote: Counting objects: 100% (7/7), done.
remote: Compressing objects: 100% (5/5), done.
remote: Total 7 (delta 1), reused 5 (delta 1), pack-reused 0
Receiving objects: 100% (7/7), done.
Resolving deltas: 100% (1/1), done.
takuto@DESKTOP-8UMKL44:~/fujiwara$ cd sampl-web-server
-bash: cd: sampl-web-server: No such file or directory
takuto@DESKTOP-8UMKL44:~/fujiwara$ ls
fujiwara  hello-git  learning-http-message  sample-web-server  simple-web-site
takuto@DESKTOP-8UMKL44:~/fujiwara$ cd sample-web-server/
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ ls
README.md
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ code .
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ curl --silent --request GET --url https://api.thecatapi.com/V1/images/search
[{"breeds":[{"weight":{"imperial":"6 - 12","metric":"3 - 5"},"id":"bure","name":"Burmese","cfa_url":"http://cfa.org/Breeds/BreedsAB/Burmese.aspx","vetstreet_url":"http://www.vetstreet.com/cats/burmese","vcahospitals_url":"https://vcahospitals.com/know-your-pet/cat-breeds/burmese","temperament":"Curious, Intelligent, Gentle, Social, Interactive, Playful, Lively","origin":"Burma","country_codes":"MM","country_code":"MM","description":"Burmese love being with people, playing with them, and keeping them entertained. They crave close physical contact and abhor an empty lap. They will follow their humans from room to room, and sleep in bed with them, preferably under the covers, cuddled as close as possible. At play, they will turn around to see if their human is watching and being entertained by their crazy antics.","life_span":"15 - 16","indoor":0,"lap":1,"alt_names":"","adaptability":5,"affection_level":5,"child_friendly":4,"dog_friendly":5,"energy_level":4,"grooming":1,"health_issues":3,"intelligence":5,"shedding_level":3,"social_needs":5,"stranger_friendly":5,"vocalisation":5,"experimental":0,"hairless":0,"natural":0,"rare":0,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/Burmese_(cat)","hypoallergenic":1}],"id":"hj7Oh-SRY","url":"https://cdn2.thecatapi.com/takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ curl --silent --request GER --url 'https:api.thecatapi.com/V1/imageThe following additional packages will be installed:
  libjq1 libonig4
The following NEW packages will be installed:
  jq libjq1 libonig4
0 upgraded, 3 newly installed, 0 to remove and 196 not upgraded.
Need to get 276 kB of archives.
After this operation, 930 kB of additional disk space will be used.
Do you want to continue? [Y/n] Y
Get:1 http://archive.ubuntu.com/ubuntu bionic/universe amd64 libonig4 amd64 6.7.0-1 [119 kB]
Get:2 http://archive.ubuntu.com/ubuntu bionic/universe amd64 libjq1 amd64 1.5+dfsg-2 [111 kB]
Get:3 http://archive.ubuntu.com/ubuntu bionic/universe amd64 jq amd64 1.5+dfsg-2 [45.6 kB]
Fetched 276 kB in 8s (34.3 kB/s)
Selecting previously unselected package libonig4:amd64.
(Reading database ... 39283 files and directories currently installed.)
Preparing to unpack .../libonig4_6.7.0-1_amd64.deb ...
Unpacking libonig4:amd64 (6.7.0-1) ...
Selecting previously unselected package libjq1:amd64.
Preparing to unpack .../libjq1_1.5+dfsg-2_amd64.deb ...
Unpacking libjq1:amd64 (1.5+dfsg-2) ...
Selecting previously unselected package jq.
Preparing to unpack .../jq_1.5+dfsg-2_amd64.deb ...
Unpacking jq (1.5+dfsg-2) ...
Setting up libonig4:amd64 (6.7.0-1) ...
Setting up libjq1:amd64 (1.5+dfsg-2) ...
Processing triggers for libc-bin (2.27-3ubuntu1) ...
Processing triggers for man-db (2.8.3-2) ...
Setting up jq (1.5+dfsg-2) ...
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ curl --silent --request GER --url 'https:api.thecatapi.com/V1/images/search?limit=3' | jq
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ curl --silent --request GER --url 'https:api.thecatapi.com/V1/images/search?limit=3' > thecat.json
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -

## Installing the NodeSource Node.js 12.x repo...


## Populating apt-get cache...

+ apt-get update
Hit:1 https://deb.nodesource.com/node_12.x bionic InRelease
Hit:2 http://archive.ubuntu.com/ubuntu bionic InRelease
Get:3 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]
Get:4 http://archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]
Hit:5 http://archive.ubuntu.com/ubuntu bionic-backports InRelease
Get:6 http://security.ubuntu.com/ubuntu bionic-security/main amd64 Packages [416 kB]
Get:7 http://archive.ubuntu.com/ubuntu bionic-updates/main amd64 Packages [644 kB]
Get:8 http://security.ubuntu.com/ubuntu bionic-security/main Translation-en [147 kB]
Get:9 http://security.ubuntu.com/ubuntu bionic-security/universe amd64 Packages [567 kB]
Get:10 http://archive.ubuntu.com/ubuntu bionic-updates/main Translation-en [239 kB]
Get:11 http://security.ubuntu.com/ubuntu bionic-security/universe Translation-en [183 kB]
Get:12 http://archive.ubuntu.com/ubuntu bionic-updates/universe amd64 Packages [954 kB]
Get:13 http://security.ubuntu.com/ubuntu bionic-security/multiverse amd64 Packages [4008 B]
Get:14 http://archive.ubuntu.com/ubuntu bionic-updates/universe Translation-en [281 kB]
Get:15 http://archive.ubuntu.com/ubuntu bionic-updates/multiverse amd64 Packages [6644 B]
Fetched 3619 kB in 16s (230 kB/s)
Reading package lists... Done

## Confirming "bionic" is supported...

+ curl -sLf -o /dev/null 'https://deb.nodesource.com/node_12.x/dists/bionic/Release'

## Adding the NodeSource signing key to your keyring...

+ curl -s https://deb.nodesource.com/gpgkey/nodesource.gpg.key | apt-key add -
OK

## Creating apt sources list file for the NodeSource Node.js 12.x repo...

+ echo 'deb https://deb.nodesource.com/node_12.x bionic main' > /etc/apt/sources.list.d/nodesource.list
+ echo 'deb-src https://deb.nodesource.com/node_12.x bionic main' >> /etc/apt/sources.list.d/nodesource.list

## Running `apt-get update` for you...

+ apt-get update
Hit:1 https://deb.nodesource.com/node_12.x bionic InRelease
Hit:2 http://security.ubuntu.com/ubuntu bionic-security InRelease
Hit:3 http://archive.ubuntu.com/ubuntu bionic InRelease
Hit:4 http://archive.ubuntu.com/ubuntu bionic-updates InRelease
Hit:5 http://archive.ubuntu.com/ubuntu bionic-backports InRelease
Reading package lists... Done

## Run `sudo apt-get install -y nodejs` to install Node.js 12.x and npm
## You may also need development tools to build native addons:
     sudo apt-get install gcc g++ make
## To install the Yarn package manager, run:
     curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
     echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
     sudo apt-get update && sudo apt-get install yarn


takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ sudo apt install -y build-essential
Reading package lists... Done
Building dependency tree... 50%
Building dependency tree
Reading state information... Done
build-essential is already the newest version (12.4ubuntu1).
The following package was automatically installed and is no longer required:
  libfreetype6
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 236 not upgraded.
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ sudo apt install -y nodejs
Reading package lists... Done
Building dependency tree
Reading state information... Done
nodejs is already the newest version (12.4.0-1nodesource1).
The following package was automatically installed and is no longer required:
  libfreetype6
Use 'sudo apt autoremove' to remove it.
0 upgraded, 0 newly installed, 0 to remove and 236 not upgraded.
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ mkdir mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ cd mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi)
version: (1.0.0)
description:
entry point: (index.js)
test command:
git repository:
keywords:
author:
license: (ISC)
About to write to /mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "description": "",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC"
}


Is this OK? (yes)
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ npm install --save express

npm notice created a lockfile as package-lock.json. You should commit this file.
npm WARN mywebapi@1.0.0 No description
npm WARN mywebapi@1.0.0 No repository field.

+ express@4.17.1
added 50 packages from 37 contributors and audited 126 packages in 6.582s
found 0 vulnerabilities

takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi)
version: (1.0.0)
description:
git repository:
keywords:
author:
license: (ISC)
About to write to /mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "^4.17.1"
  },
  "devDependencies": {},
  "description": ""
}


Is this OK? (yes)
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ npm init
This utility will walk you through creating a package.json file.
It only covers the most common items, and tries to guess sensible defaults.

See `npm help json` for definitive documentation on these fields
and exactly what they do.

Use `npm install <pkg>` afterwards to install a package and
save it as a dependency in the package.json file.

Press ^C at any time to quit.
package name: (mywebapi)
version: (1.0.0)
description:
git repository:
keywords:
author:
license: (ISC)
About to write to /mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/package.json:

{
  "name": "mywebapi",
  "version": "1.0.0",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "author": "",
  "license": "ISC",
  "dependencies": {
    "express": "^4.17.1"
  },
  "devDependencies": {},
  "description": ""
}


Is this OK? (yes) yes
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ npm install --save express
npm WARN mywebapi@1.0.0 No description
npm WARN mywebapi@1.0.0 No repository field.

+ express@4.17.1
updated 1 package and audited 126 packages in 5.918s
found 0 vulnerabilities

takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano index.js
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ rm mywebapi
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ ls
index.js  node_modules  package-lock.json  package.json
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
Listening on port 3000
^C
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ cd
takuto@DESKTOP-8UMKL44:~$ cd /fujiwara
-bash: cd: /fujiwara: No such file or directory
takuto@DESKTOP-8UMKL44:~$ cd fujiwara
takuto@DESKTOP-8UMKL44:~/fujiwara$ cd sample-web-server/
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3'
[{"breeds":[],"categories":[{"id":5,"name":"boxes"}],"id":"5jb","url":"https://cdn2.thecatapi.com/images/5jb.gif","width":250,"height":146},{"breeds":[],"id":"b43","url":"https://cdn2.thecatapi.com/images/b43.jpg","width":500,"height":333},{"breeds":[],"id":"e0j","url":"https://cdn2.thecatapi.com/images/e0j.jpg","width":600,"height":450}]takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server$ cd mywebapi/
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ ls
index.js  node_modules  package-lock.json  package.json
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano index.js
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/index.js:14
        { title: "Web APIを作る', done: false }
                 ^^^^^^^^^^^^^^^^^^^^^^^^^^^

SyntaxError: Invalid or unexpected token
    at Module._compile (internal/modules/cjs/loader.js:718:23)
    at Object.Module._extensions..js (internal/modules/cjs/loader.js:785:10)
    at Module.load (internal/modules/cjs/loader.js:641:32)
    at Function.Module._load (internal/modules/cjs/loader.js:556:12)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano index.js
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ node index.js
Listening on port 3000
^C
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ nano index.js
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ mkdir web
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ cd web
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ nano index.html
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ nano index.html
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ node index.js
internal/modules/cjs/loader.js:626
    throw err;
    ^

Error: Cannot find module '/mnt/c/Users/mizut/Documents/fujiwara/sample-web-server/mywebapi/web/index.js'
    at Function.Module._resolveFilename (internal/modules/cjs/loader.js:623:15)
    at Function.Module._load (internal/modules/cjs/loader.js:527:27)
    at Function.Module.runMain (internal/modules/cjs/loader.js:837:10)
    at internal/main/run_main_module.js:17:11 {
  code: 'MODULE_NOT_FOUND',
  requireStack: []
}
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ cd .
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ cd mywebapi
-bash: cd: mywebapi: No such file or directory
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ cd /mywebapi
-bash: cd: /mywebapi: No such file or directory
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ cd -
/mnt/c/ubuntu_home/fujiwara/sample-web-server/mywebapi/web
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ cd -
/mnt/c/ubuntu_home/fujiwara/sample-web-server/mywebapi/web
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ cd ‐
-bash: cd: ‐: No such file or directory
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi/web$ cd
takuto@DESKTOP-8UMKL44:~$ cd fujiwara/sample-web-server/mywebapi/
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ c
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ cnano index.html
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ cnode index.js
Listening on port 3000
^C
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ curl --silent --request GET --url https://api.thecatapi.com/v1/images/search
[{"breeds":[],"categories":[{"id":14,"name":"sinks"}],"id":"MTc5MTY4MA","url":"https://cdn2.thecatapi.com/images/MTc5MTY4MA.jpg","width":612,"height":612}]takuto@DESKTOP-8UMKL44:~/fujiwarl 'https://api.thecatapi.com/v1/images/search?limit=3'GET --ur
[{"breeds":[],"id":"b97","url":"https://cdn2.thecatapi.com/images/b97.jpg","width":500,"height":667},{"breeds":[],"id":"MTY0NjU4Mg","url":"https://cdn2.thecatapi.com/images/MTY0NjU4Mg.jpg","width":1600,"height":1200},{"breeds":[{"weight":{"imperial":"4 - 10","metric":"2 - 5"},"id":"csho","name":"Colorpoint Shorthair","cfa_url":"http://cfa.org/Breeds/BreedsCJ/ColorpointShorthair.aspx","vcahospitals_url":"https://vcahospitals.com/know-your-pet/cat-breeds/colorpoint-shorthair","temperament":"Affectionate, Intelligent, Playful, Social","origin":"United States","country_codes":"US","country_code":"US","description":"Colorpoint Shorthairs are an affectionate breed, devoted and loyal to their people. Sensitive to their owner’s moods, Colorpoints are more than happy to sit at your side or on your lap and purr words of encouragement on a bad day. They will constantly seek out your lap whenever it is open and in the moments when your lap is preoccupied they will stretch out in sunny spots on the ground.","life_span":"12 - 16","indoor":0,"lap":1,"alt_names":"","adaptability":3,"affection_level":4,"child_friendly":4,"cat_friendly":3,"dog_friendly":4,"energy_level":4,"grooming":2,"health_issues":2,"intelligence":5,"shedding_level":3,"social_needs":4,"stranger_friendly":2,"vocalisation":5,"bidability":4,"experimental":0,"hairless":0,"natural":0,"rare":0,"rex":0,"suppressed_tail":0,"short_legs":0,"wikipedia_url":"https://en.wikipedia.org/wiki/Colorpoint_Shorthair","hypoallergenic":0}],"id":"oSpqGyUDS","url":"https://cdn2.thecatapi.com/images/oSpqGyUDS.jpg","width":1363,"height":1600}]takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ curl --silent -rl 'https://api.thecatapi.com/v1/images/search?limit=3' | jq
[
  {
    "breeds": [],
    "id": "2gh",
    "url": "https://cdn2.thecatapi.com/images/2gh.jpg",
    "width": 500,
    "height": 375
  },
  {
    "breeds": [],
    "categories": [
      {
        "id": 1,
        "name": "hats"
      }
    ],
    "id": "7gk",
    "url": "https://cdn2.thecatapi.com/images/7gk.jpg",
    "width": 1024,
    "height": 768
  },
  {
    "breeds": [],
    "id": "iYklU8s_D",
    "url": "https://cdn2.thecatapi.com/images/iYklU8s_D.jpg",
    "width": 730,
    "height": 897
  }
]
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$ curl --silent --request GET --url 'https://api.thecatapi.com/v1/images/search?limit=3' > thecat.json
takuto@DESKTOP-8UMKL44:~/fujiwara/sample-web-server/mywebapi$

```
