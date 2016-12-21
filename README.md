# sequelize_notes

###

install sequelize globally with `npm install -g sequelize-cli`

### Results of `sequelize init`

Created "config/config.js"
Deleting the migrations folder. (--force)
Successfully deleted the migrations folder.
Successfully created migrations folder at "/Users/zebgirouard/Coding/angular_sequalize_tutorial/server/migrations".
Deleting the seeders folder. (--force)
Successfully deleted the seeders folder.
Successfully created seeders folder at "/Users/zebgirouard/Coding/angular_sequalize_tutorial/server/seeders".
Deleting the models folder. (--force)
Successfully deleted the models folder.
Successfully created models folder at "./server/models".

The tutorial is inconsistent on where it thinks `config.js` is.  This causes problems.

If you see this error: `Please install 'pg' module manually`

Run this: `npm install -g pg`

Connection to postgres looks like this:

`postgres://zebgirouard@localhost:5432/bookmark` where `zebgirouard` should be replaced by local username.
