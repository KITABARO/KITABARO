### Hi there 👋

** Hi there!**

I'm kitabaro, I'm still learning...

I'm always looking for new ways to improve my skills and learn new technologies. I'm currently learning about:

* **C#**
* **ASP.NET CORE**
* **REST API**

* **Rotating text:**

```javascript
var text = "kitabaro";

var rotateText = function() {
  var currentText = text.charAt(0);
  text = text.substring(1) + currentText;
  document.getElementById("rotatingText").innerHTML = text;
};

setInterval(rotateText, 100);
```

* **Fading text:**

```javascript
var text = "kitabaro";

var fadeText = function() {
  var opacity = document.getElementById("fadingText").style.opacity;
  if (opacity > 0) {
    opacity -= 0.01;
  } else {
    opacity = 1;
  }
  document.getElementById("fadingText").style.opacity = opacity;
};

setInterval(fadeText, 100);
```


* **C#:**

```markdown
* **C#:** <i class="fab fa-csharp"></i>
```

* **ASP.NET Core:**

```markdown
* **ASP.NET Core:** <i class="fab fa-aspnet-core"></i>
```

* **REST API:**

```markdown
* **REST API:** <i class="fas fa-api"></i>
```
