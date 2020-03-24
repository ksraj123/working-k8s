# working-k8s

conditions for this to work

change the wait4db.js file line number 43 to

(process.env.MONGO_URL || 'mongodb://'+settings.database.server+':'+settings.database.port+'/')+settings.database.name,

create a db folder inside docker directory
