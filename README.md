# blog-post-card

body {
 background-color: ivory;

}

.blog-post-card {
background-color: white;
 border-radius: 20px;
 width: 370px;
 text-align: center;
}

.post-img{
  width: 100%;
  padding: 0px;
  border-bottom:5px solid #ccc;
}

.post-content{
  padding:10px;
  text-align: center;
}

 .post-title{
    color:brown;
    margin:10px 0;
 }

.post-excerpt{
  color: brown;
  margin:20px 0;
}

 
 .read-more {
  display: inline-block;
  background-color: #007bff;
  color: white;
  padding: 10px 16px;
  border-radius: 6px;
  text-align: center;
  text-decoration: none;
  margin:10px;
 
}

#html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blog Post Card</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="blog-post-card">
    <img class="post-img"
    src="https://cdn.freecodecamp.org/curriculum/labs/cover-photo.jpg"
    alt="a working laptop"
    >


<div class="post-content">

    <h2 class="post-title">How to be successful.</h2>
<p class="post-excerpt">Success doesn’t come overnight — it grows from small, consistent efforts every single day. Stay focused on your goals, keep learning from your mistakes, and never give up when things get difficult. With patience, discipline, and a positive mindset, you can achieve more than you imagine.By-
Tanushree Padole Mam</p>
<a class="read-more"
href="https://www.freecodecamp.org"
      target="_blank"
    >
Read More</a>
</div>

</div>

</body>
</html>


.read-more:hover {
  background-color: #0056b3;
}
