Society Pro Playbook 
====================

View the playbook generated by this repo at http://societypro.github.io/playbook/

Developer Usage
---------------

### Dependencies:
You first need npm and nodejs.

### Build the Playbook:

```
npm install -g grunt grunt-cli
cd playbook
git checkout stackedit
npm install
grunt bower:install
grunt
http-server
firefox localhost:8080/src/playbook.html
```

### Edit or add Markdown under the src directory


### Add Jade code that loads the markdown into a template 
In general you will add a line like: `include:md teamwork/test.md`
See also: [jade reference](http://jade-lang.com/api/), [markdown reference](http://daringfireball.net/projects/markdown/syntax)