# myreads-harperdb

This is an entry project for Hashnode-Harperdb Hackathon.

Myreads is a web-based application that lets you manage your bookshelf digitally. Here you can maintain the status of the books in three categories.

```
1. Wish List: Books which you want to read.
2. Reading List: Books you're currently reading.
3. Finished List: Books you finished reading.
```

# Run the project

Make sure you've [docker](https://docs.docker.com/engine/install/) and [docker-compose](https://docs.docker.com/compose/install/) installed.

Clone the repo with its submodules.

```
git clone --recurse-submodules https://github.com/pratikjagrut/myreads-harperdb.git
cd myreads-harperdb
```

Update the `.env` file with yor harperDB database credentials.

Run the `docker-compose up` command.

Once everything starts successfully you can hit http://locahost:3000 in browser.