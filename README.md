# graphql-tutorial

graphql tutorial for beginner

# installation

npm install
npm i notarealdb
npm run

# query 1

{
greeting
students {
id
firstName
lastName
}
}

# query 2

{
 studentById(id:"S1001") {
id
firstName
lastName
}
}

# query 3

{
students{
id
fullName
}
}

# query 4

{
students{
id
firstName
college {
id
name
location
rating
}
}
}
