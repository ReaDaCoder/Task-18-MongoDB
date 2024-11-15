# Task-18-MongoDB

//Create a database and name it Codetribe.
test> use Codetribe
switched to db Codetribe
Codetribe>

//Create collections named Facilitators, Trainees and Projects.
Codetribe> db.createCollection("Facilitators")
{ ok: 1 }
Codetribe> db.createCollection("Trainees")
{ ok: 1 }
Codetribe> db.createCollection("Projects")
{ ok: 1 }
Codetribe>

//For Facilitators collection insert a document that contains the following fields: 
//Name
//Location
//Course
Codetribe> db.Trainees.insertOne({name:"Reabetswe",location:"TIH",facilitator:"Vukona"})
{
  acknowledged: true,
  insertedId: ObjectId('67374e83ec04a4822a0d8191')
}

//For Projects collection insert a document that contains the following fields: 
//Name
//Course
//Lesson
Codetribe> db.Projects.insertOne({name:"Employee App", Course:"Full Stack Web Development", lesson:5})
{
  acknowledged: true,
  insertedId: ObjectId('67374fdbec04a4822a0d8192')
}


