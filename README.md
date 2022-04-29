<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>/* 
Define this in your CSS 
.bgColor = Replace it by the name you want to give your animation
.bgAnimObj = Assign this class to the object you want to apply the effect
*/

.bgAnimObj {
	background: #1abc9c;
	/* Chrome, Safari */
	-webkit-animation: bgColor 5s;
	/* Firefox */
	-moz-animation: bgColor 5s;
	/* Standard Syntax */
	animation: bgColor 5s;
}

/* 
Define the keyframe and changes
*/

/* Chrome, Safari */
@-webkit-keyframes bgColor {
	from {
 		background: #1abc9c;
	} 
	to {
 		background: #ebebeb;
	}
}

/* Firefox */
@-moz-keyframes bgColor {
    from {
        background: #1abc9c;
    }
    to {
        background: #ebebeb;
    }
}

/* Standard syntax */
@keyframes bgColor {
	from {
		background: #1abc9c;
	}
	to {
		background: #ebebeb;
	}
}
Ruslan</title>
    <!-- Bootstrap -->
    <link href="css/bootstrap-4.4.1.css" rel="stylesheet">
    <style type="text/css">
    .container .row .col-12.mb-2.text-center h1 {
	font-family:"yeseva-one"

}
    .container .row .col-12.mb-2.text-center h1 {
	font-family:Allenoire Free Personal;
}
    </style>
  </head>
  <body>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">

      <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation"> <span class="navbar-toggler-icon"></span> </button>
    </nav>
    <section>
      <div class="container">
        <div class="row"></div>
      </div>
      <div class="container ">
        <div class="row"></div>
        <div class="row"></div>
        <div class="row"></div>
      </div>
      <div class="container">
        <div class="row">
          <div class="col-12 mb-2 text-center"><h1><strong>Ruslan</strong></h1>
          </div>
        </div>
        <div class="row"></div>
      </div>
    </section>
    <div class="container">
      <div class="row">
        <div class="col-12 col-md-8 mx-auto offset-xl-1 col-xl-12">
          <div class="jumbotron">
            <div class="row text-center">
              <div class="text-center col-12">
                <h2>Что-то хочешь мне сказать?</h2>
              </div>
              <div class="text-center col-12">
                <!-- CONTACT FORM https://github.com/jonmbake/bootstrap3-contact-form -->
                <form id="feedbackForm" class="text-center">
                  <div class="form-group">
                    <label for="name">имя</label>
                    <input type="text" class="form-control" id="name" name="name" placeholder="Name" aria-describedby="nameHelp">
                    <span id="nameHelp" class="form-text text-muted" style="display: none;">Please enter your name.</span>
                  </div>
                  <div class="form-group">
                    <label for="email" class="page-item">&nbsp;email</label>
                    <input type="email" class="form-control" id="email" name="email" placeholder="Email Address" aria-describedby="emailHelp">
                    <span id="emailHelp" class="form-text text-muted" style="display: none;">askarovruslanr@mailru.</span>
                  </div>
                  <div class="form-group">
                    <label for="message">Письмо:</label>
                    <textarea rows="10" cols="100" class="form-control" id="message" name="message" placeholder="Message" aria-describedby="messageHelp"></textarea>
                    <span id="messageHelp" class="form-text text-muted" style="display: none;">Please enter a message.</span>
                  </div>
                  <button type="submit" id="feedbackSubmit" class="btn btn-primary btn-lg"> Отправить&nbsp;</button>
                </form>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <footer class="text-center">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <p>домашний сайт</p>
          </div>
        </div>
      </div>
    </footer>
    <!-- jQuery (necessary for Bootstrap's JavaScript plugins) --> 
    <script src="js/jquery-3.4.1.min.js"></script> 
    <!-- Include all compiled plugins (below), or include individual files as needed --> 
    <script src="js/popper.min.js"></script> 
    <script src="js/bootstrap-4.4.1.js"></script>
  </body>
</html>
