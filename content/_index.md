+++
title = "My presentation"
outputs = ["Reveal"]
[reveal_hugo]
theme = "moon"
+++

# Hello world!

This is my first slide.

---

# Second slide!

This is a test

---

# Third slide

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} Two {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

{{< slide transition="zoom" transition-speed="fast" >}}

# Fourth slide

change transition

---

{{< slide background-color="#FF4081" >}}

# Fifth slide

change background color

---

{{< slide background-image="https://static01.nyt.com/images/2010/12/19/magazine/19URBAN-1/19URBAN-1-jumbo.jpg?quality=90&auto=webp" >}}

# Sixth slide

---

# Seventh slide

<img src="https://static01.nyt.com/images/2010/12/19/magazine/19URBAN-1/19URBAN-1-jumbo.jpg?quality=90&auto=webp" border="0px" height="300px">

---

# Eight slide

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

---

Combining elements

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} <img src="https://static01.nyt.com/images/2010/12/19/magazine/19URBAN-1/19URBAN-1-jumbo.jpg?quality=90&auto=webp" height="300px"> {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

End!
