<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <!-- font awesome -->
    <script src="https://kit.fontawesome.com/27a9e349a3.js" crossorigin="anonymous"></script>
<!-- google font -->
<link href="https://fonts.googleapis.com/css?family=Candal|Lora&display=swap" rel="stylesheet">
    <!-- custom styling -->
<link rel="stylesheet" href="../../css/style.css">
    <!-- custom styling -->
    <link rel="stylesheet" href="../../css/admin.css">

    <title>Admin Section - Add Posts</title>
</head>
<body>
    <header> 
        <div class="logo">
            <h1 class="logo-txt"><span>pkpure</span>kanxa</h1>
        </div> 
        <i class="fa fa-bars menu-toggle"></i>
        <ul class="nav">
            <li>
                <a href="#">
                    <i class="fa fa-user"></i>
                    pkpurekanxa
                    <i class="fas fa-chevron-down" style="font-size: .8em;" ></i>
                </a>
             <ul>
                   
                    <li><a href="#" class="logout">logout</a> </li>
             </ul>
            </li>
            

        </ul>
            

        
    </header>
    <!-- admin page wrapper-->
    <div class="admin-wrapper">
        <!--left sidebar-->
        <div class="left-sidebar">
            <ul>
                <li><a href="index.html">Manage Posts</a></li>
                <li><a href="../users/index.html">Manage Users</a></li>
                <li><a href="../topics/index.html">Manage Topics</a></li>
            </ul>

        </div>
        <!--//left sidebar-->
        <!-- admin content-->
        <div class="admin-content">
            <div class="botton-group">
                <a href="create.html" class="btn btn-big">Add post</a>
                <a href="index.html" class="btn btn-big">Manage post</a>
            </div>
            <div class="content">
                <h2 class="page-title">Manage posts</h2>
                <form action="create.html" method="post">
                    <div>
                        <label>Title</label>
                        <input type="text" name="title" class="text-input">
                    </div>
                    
                    <div class="container">
                       <label>Body</label> 
                        <br>
                        <textarea name="Body" id="editor" cols="100" rows="50"></textarea>
                    </div> 
                    <div>
                        <label>Image</label>
                        <input type="file" name="image" class="text-input">
                    </div>
                    
                    <div>
                        <label>Topics</label>
                        <select name="topic" class="text-input">
                            <option value="portry">poetry</option>
                            <option value="life lessons">life lessons</option>
                        </select>
                    </div>
                    <div>
                        <button type="submit" class="btn btn-big">Add Post</button>
                    </div>

                </form>
            </div>
        </div>
        <!-- //admin content-->
    </div>
    <!--//page wrapper       -->
 
   
    <!--jquery-->
    <script 
    src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.4.1/jquery.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
      
    <!--ckeditor -->
    <script 
    src="https://cdn.ckeditor.com/ckeditor5/[version.number]/[distribution]/ckeditor.js"></script>
   
    
    <!--custom script -->
    <script src="../../js/scripts.js"></script>
</body>
