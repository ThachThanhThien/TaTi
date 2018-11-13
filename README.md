
//insert
User.create({ username: 'barfooz', isAdmin: true }, { fields: [ 'username' ] }).then(user => {
  // let's assume the default of isAdmin is false:
  console.log(user.get({
    plain: true
  })) // => { username: 'barfooz', isAdmin: false }
})


//update
// way 1
task.title = 'a very different title now'
task.save().then(() => {})

// way 2
task.update({
  title: 'a very different title now'
}).then(() => {})
