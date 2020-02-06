Title: Theme
Date: 2020-02-05 17:35
Category: Articles

This site is styled with this CSS:

```
html, body {
  width: 100%;
  min-height: 100%;
  margin: 0;
  padding: 0;
  position: absolute;
}

body {
  height: 100%;
  display: flex;
  flex-direction: column;
}

#banner {
  background-color: #ccc;
  padding: 10px;
}

header h1 {
  margin: 0;
  font-family: sans-serif;
}

header h1 a {
  color: black;
  text-decoration: none;
  font-weight: normal;
}

#menu ul {
  display: flex;
  background-color: #ccc;
  margin: 0;
  padding: 10px;
}

#menu li {
  list-style: none;
  padding: 0 10px;
}

#content {
  width: 800px;
  margin: auto;
  flex-grow: 1;
}

#contentinfo {
  background-color: #ccc;
  padding: 10px;
}
```
