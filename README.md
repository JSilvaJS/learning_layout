# Synopsis
The goal is to use the HTML code below and draft up CSS to mimic the Example Image (also shown below).

# Used HTML Code
``` html
<!DOCTYPE html>
<html>
<head>
  <title>Octocats</title>
</head>
<body>

  <ul class="octodex">
    <li class="octocat">
      <a href="https://octodex.github.com/saritocat">
        <img src="https://octodex.github.com/images/saritocat.png" />
      </a>
      <div class="image-footer">
        <span class="image-number">115</span>
        <div class="image-caption">
          <span>the</span>
          <a href="https://octodex.github.com/saritocat">Saritocat</a>
          <span>by</span>
          <ul class="authors">
            <li>
              <a href="https://github.com/JohnCreek">
                <img src="https://github.com/JohnCreek.png" />
              </a>
            </li>
          </ul>
        </div> <!-- .image-caption -->
      </div> <!-- .image-footer -->
    </li>
    <li class="octocat">
      <a href="https://octodex.github.com/topguntocat">
        <img src="https://octodex.github.com/images/topguntocat.png" />
      </a>
      <div class="image-footer">
        <span class="image-number">114</span>
        <div class="image-caption">
          <span>the</span>
          <a href="https://octodex.github.com/topguntocat">Topguntocat</a>
          <span>by</span>
          <ul class="authors">
            <li>
              <a href="https://github.com/leereilly">
                <img src="https://github.com/leereilly.png" />
              </a>
              <a href="https://github.com/jeejkang">
                <img src="https://github.com/jeejkang.png" />
              </a>
              <a href="https://github.com/tonyjaramillo">
                <img src="https://github.com/tonyjaramillo.png" />
              </a>
            </li>
          </ul>
        </div> <!-- .image-caption -->
      </div> <!-- .image-footer -->
    </li>
    <li class="octocat">
      <a href="https://octodex.github.com/carlostocat">
        <img src="https://octodex.github.com/images/carlostocat.gif" />
      </a>
      <div class="image-footer">
        <span class="image-number">113</span>
        <div class="image-caption">
          <span>the</span>
          <a href="https://octodex.github.com/carlostocat">Carlostocat</a>
          <span>by</span>
          <ul class="authors">
            <li>
              <a href="https://github.com/jeejkang">
                <img src="https://github.com/jeejkang.png" />
              </a>
            </li>
          </ul>
        </div> <!-- .image-caption -->
      </div> <!-- .image-footer -->
    </li>
  </ul>

</body>
</html>
```
# Example Image
![alt text](https://tiy-learn-content.s3.amazonaws.com/39d9add7-octodex.png)

# Sample Code
``` CSS
.octodex {
	border: 1px solid #DBDBDB;
	overflow: hidden;
	padding-bottom: 90px;
	padding-top: 10px;
	padding-right: 60px;
	padding-left: 150px;
}

img {
	height: 200px;
}

.octocat img {
	border: 1px solid #DBDBDB;
	float: left;
}

.authors img {
	height: 20px;
	width: 20px;
	position: relative;
	top: -18px;
	right: -53px;
	float: right;
}
```


