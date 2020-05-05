# LoginApp
Front end and backend compressed into two separate zip files

Unzip both the files and run separately
Note: Database is created on MongoDB Cloud (Atlas) so it won't allow connection from a different IP address unless its whitelisted.

Hence, i am writing my datbase details and data format here:

Database Name: Test
Collection Name: users
Format:

Schema / Data format:

userSchema = new Schema {
username: {type: String},
password: {type: String},
firstname: {type: String}
lastname: {type: String}

}
