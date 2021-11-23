To create the best simple cooking recipe website, we need more than a heading and paragraphs.
Lets first do the following:

1. Choose a cooking recipe of your choice.

2. Write the recipe’s title as a heading of your choice.

3. And a simple description using the paragraph tag.

   For us we choose Caesar Salad, do not judge it is easy to explain. The website will look like this

![screenshot](https://lh3.googleusercontent.com/Yqiyo19HXCLzkBxD2Kwkn4rZdhqSBim8L8FdpLgh2O8fBc2olbRI_ISskkfB7_-oh5V9CDNVo1HrO5olUm5WkMY8xRMfCv1ahGyExsLhEKgx62qrLl9pNTXp76T7GlpI4JdjPzcR" alt="img" style="zoom:80%;)

Just by writing this code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Cooking Recipe</title>
  </head>
  <body>
    <h2>Caesar Salad Recipe</h2>
    <p>Simple salad that can be done in 15 minutes</p>
  </body>
</html>
```

> Now we are ready to learn more tags.

**01_Images**

Rarely do we enter a website that has zero images. Let us now learn images, it is one of the special tags
It looks like this:

```html
<img src="" alt="" />
```

Lets see, it is new to us that we have a starting tag without a closing tag, this type of tag is called self-closing tag.
**📝 Note: **

> `src` and `alt` are called tag attributes, now to see what each one does.

```
Src : is short for source, and that would be the image link or path.
Alt : is short for alternative text, which when an image does not work the text will appear.
The mean use of alt is for the unfortunate users who are not able to see.
```

Now to be able to implement this tag, we have two choices:

1. Type 1: Either adding a local image that depends on

2. Type 2: Adding public/ general images link from the web

   Let's take a look at how to implement both types.

**Type 1 - Local Images:**

Source in this case as following:

1.  Create a folder in your file by doing the following

![screenshot](https://lh3.googleusercontent.com/3rVdAypOBV3GvA2lr5VxmFOqthJKE5l8WeIiEPubAEj37xa1g1fym7dZOzVAqzdmz6NVDK6gbOsc4X_KvYWft5ae_MFpW4KBCZM_jHqlQOhKVKidh3V1wYKH-DozyJ1aQm7HU5c5" alt="img" style="zoom:67%;)

2. Name the folder with a meaningful names, I will call mine `images`

3. Import an image from the web by choosing `save image as`

4. Choose wisely where to place your image, respect your path

   `Desktop -> Web Course -> Cooking Recipe -> images`

   Your folder should look like this:

   ![img](https://lh3.googleusercontent.com/byhUw5A3MvhUk-It92jODFdD1IlYWsjiX3E8XyrwgvdTFDGxpTdfu1nQ_NPs4j5JOQDPW_s6gmWWBzvyeFkl36Vh-AgYI6pId1_c94aytYqyMI8teNPet4IeaAFvnHhYKKWsZUW-)

5. Do as bellow in your code

```html
<img src="images/salad.jpg" alt="salad image" />
```

**📝 Note:**

> You will notice that the code auto-filling it self if you right your path the correct way

![img](https://lh6.googleusercontent.com/npb0yD2-cPpPVtTi0AmxwMPU5i2oSDixcOY8xevxIXuA7ErCJUieFrV4rH7b5WWgpK9V5JpMcS2UQulld69I1mcQpIudQ4b7ZV52L3Dm7LHjvTBjyXP9w8lx-KAOUsEUbz3ZPP7z)

After saving and refreshing the page, this id my result:

![img](https://lh5.googleusercontent.com/ieVqZB367vQXKVqqkTCtjEHFS3NRytEao312h0Ia64UiAtjU9WIq3eJtuaIZRszEr3EtAlIItWwneYjgrjZpyYUd8itG0ncMETd7WEsAOosdNXzWYGkIpuejiJrtDTp_CsnR6lAm)

**📝 Note:**

> Oooooh we have an issue now, the size is making our website look bad.
> Ammmm 🤔

**⚠ Quick Fix:**

> There are two things to add in the tag itself, which are:
> height
> width
> You should use only one, either height or width so our images dont get stretched or any issues that ruin the image's quality.

```html
<img src="images/salad.jpg" alt="salad image" height="120px" />
```

> Once we tried the height we will get:

![img](https://lh3.googleusercontent.com/ohc3QxBxNtITMu2VO_BjQ9ztn9efT34wtg-u5kG7X_BB28NiefF9qfd5uMoRXZyZMGbzSGFp3yWsLytzaJUszUh65HvXe82iPKOYfGt4_RC-U19UTiqZQRGmyYNV9-XowKv_gZnX)

Much better 😌💙
The code was used had something new 👀
**📝 Note: **

> `px` is one of the websites units, it is like saying 3 meters or 5 seconds.
> And that the image locally must end with the image format (png, jpg, ect)

**Type 2 - Public Images:**

Source would be in this case will follow this path:

1. Choosing a picture from the web
2. Right click
3. `copy image address`
4. paste it in the source placement

![img](https://lh3.googleusercontent.com/MBaJNZ82yfM-r1nAh5FoZR6CR8cSL1iM76ypXuCydtOCXbz5XVZr1QKoOKiRW1RcNPFlQfxqzT2P6qHJOxDhOolCCJe-E2-LkeFy3bcgI2xoKkgX1OQsBLqjr5P5jSlC8fFqbHrf)

Code would be this way:

```html
<img
  src="https://www.recipetineats.com/wp-content/uploads/2016/05/Caesar-Salad_7-SQ.jpg"
  alt="salad image"
  height="120px"
/>
```

Let us see how the website looks:

![img](https://lh6.googleusercontent.com/8Q1xmkZrF8z4n4pD1-Nq1Tk3BJa31gk5KWHQUalKvHJRNQyJFhW7Nz8tH_GfIqXX1GR-QvkSH2W-mquIIsCDEU3vR1lZg_deh4SSC4-ZCrl0K1P7fsFYh80M1pW7_cuCG9Z2z1Qf)

**⚠ Simple Fixes:**

> Notice something in our URL?
>
> **![img](https://lh5.googleusercontent.com/1BAA80GySwxk3CfsT7Z_jCCZDvgsJVKboUb4QJVJsIQdTQim2_5lX9PIC4sidAh2nJNy5vpvbmjx23vjLTj3s3gNBoAHlvqw4iF5NzZ9HxP3uNzFMTSXVwYKqxAZU-yOBM2O138F)**

> The `%20` is making our link not desirable, links like this are always suspicious 😂
> Let us fix it!!!! 👀
> This will be removed once we remove the spaces in our folder names ✔
>
> ![img](https://lh6.googleusercontent.com/3s-CgUIpC2HU8dN1aD9b-zlyDbQq_tqNdzw-LjRPcJu4hrj2ZyFzFl4-Y1txU1XNlQ1B0eWgtWgIB_g0-xudO64SLGcmNYLJTYRagnO-X39PV7H8la_PXnC8Bwd_d_r1gyqYNzwZ)

**📝 Note:**

> We will use something called `camel case method` which is writing all in small letters, until we reach a new word
>
> ![image-20210613181044589](C:\Users\Malba\AppData\Roaming\Typora\typora-user-images\image-20210613181044589.png)

> Notice how we started the first word with all small letters, and then when we started with a new word the first letter became capital.
> Our folders after renaming, it becomes:

![img](https://lh4.googleusercontent.com/CoG7ukDLsWZDyco0aGYXwbutAZYzrGoi3xb3kzV2a1D8dwm1DCABZuFH_IwFSesBVwPzfe3cNeFoAKok-qNBRM04S-U6FUG7CnEqtS5_ClhNkngUw-89oez-X0a1Shoh1Ht8-0j5)

Notice now how our link is so clean and meaningful. 😍
Final code looks like:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Cooking Recipe</title>
  </head>
  <body>
    <h2>Caesar Salad Recipe</h2>
    <p>Simple salad that can be done in 15 minutes</p>
    <img src="images/salad.jpg" alt="salad image" height="120px" />
    <img
      src="https://www.recipetineats.com/wp-content/uploads/2016/05/Caesar-Salad_7-SQ.jpg"
      alt="salad image"
      height="120px"
    />
  </body>
</html>
```

**02_Links**

Links are another important thing that HTML provides, they help users transport between web pages. Web pages like images have two types that we can use:

**Type 1 - Local Links:**

Like what we mean in images, local here means other pages in the same website. It is the time to create other pages, Wohooooo 😎

By doing the same steps to create the `index.html` page:

1. Create a file

   ![img](https://lh4.googleusercontent.com/Y3CbH1DlSeTMBTrRsimysZiBT3djNntU6Htf9UrwjT2k3Z4YBCePmdLm-7Evmsgvp7ug0Pjw1uL-pouSBZIdHQXDdrAgGBPJYfgFUvQUtVYa_PVpLMdzru3fgurPyRqRPpfutcLF)

2. Name it wherever you like, this time you have the freedom to do that

   **For me:** I will call it `steps.html`

   ![img](https://lh5.googleusercontent.com/5OXtoUnM7EHOEv3ccYjjGY5wpZeNbeJMCvtRZgJkEOew3Q4RmpCI8qeqHXN5_8lh22i0BM7DwaCPVQIi-K8peuqajWNK7KnxqsuqtVO_ZRgBGei3Br0EoD9eTaoHN5vPBvENoWA2)

3. Go back to our `index.html`

4. Let's put the link tag:

   ```html
   <a href=""></a>
   ```

   `<a>` is short for anchor which has the meaning of connecting your website to another place through an anchor.

   <img src="C:\Users\Malba\AppData\Roaming\Typora\typora-user-images\image-20210613181551964.png" alt="image-20210613181551964" style="zoom: 80%;" />

   I hope this image makes a better view of how HTML sees it.

   **⚠ Common Mistakes:**

   > Notice where did I place the new html page:
   >
   > ![img](https://lh3.googleusercontent.com/niIzLYBJYENLQbTNNu5Tps_8mXMe7kuCv34bz8uqFNl93IV4B0g5Ry0vpgRsrm2UjRFNt8qnm5T-7N5DTkBltcq3xvJYw6Ut_48lwTb5oGsaPPBsIqhTKPhw5K38NbVnWWyymXW-)
   >
   > It is on the same level of the `index.html`, if your page is not like this just drag it like this:
   >
   > ![img](https://lh4.googleusercontent.com/u0vSpMGooH-pj8JLrl0jSzjmbGZmqUW_CdMt8_a6VZ9PUfcWVzU2DPD-CPeEH1kR9DOgJI2di3b_VWMXY7U-Ja9tGV_IttSxSEggXrRHMWs5dhxuW3qEQUn_2SLDDSHkdYziPW_W)
   >
   > This will be helpful for step 5

5. Put the `steps.html` in the `href`, it will auto fill it

   ![img](https://lh6.googleusercontent.com/SPUoIYsMcJMW7yxum2Irym1y7MoMpr2bEGeXTpfRkkWsUbrKF9Bq1EenrjBWVuXZvvxbqRevqolMRaLYkIi_Pp7tCZxXhHtgVBeUaeR0BDaLvfuh00acPYNl0draZoFq1R0WS7yL)

6. Save and refresh 😉

   Let us see:

   ![img](https://lh6.googleusercontent.com/gU1PDJYbFPSfFo8LyrMh09nE4pdStGYvCrInuk7-K9t5obMDy-cax0LHR79HZc2Opt9m3bUW2TlDeW_uUQrfU69vyWu_NvBkFQZREIk6StRQhpE5kq-mfMbUqa0ak41lq1U3qOMB)

   Where is your link? 😱

   **📝 Note:**

   > So if you see the `<a>` tag closely, it is one of the tags that has an opening and an ending. We can write `click here` so the person can easily click on it. Try it 😁

   ```html
   <a href="steps.html">Click here</a>
   ```

   Now lets see how it looks:

   ![img](https://lh4.googleusercontent.com/RIvThFlA9zefUEeJNlAOaXEnpfoaJKSo4vw2rT1ZZgLI7tpL9tIBBe-skiNNXO6W8ceGB87_s8w7XJC6X5eIAcn80fl95_w5a4O3pXE0hrVKvWBsD0aZCs7jm-xiDdr_pu8JlxDv)

   Once we click on it it will do the following:

   ![img](https://lh3.googleusercontent.com/q0yoknU-PA6sV67rA5mXFvmxFpnki7qMmPuD76bkil9gD_baf5ghK4m7giUrJvA1WtWzAs0alWI84rkFkBXcuRfbTxGkWS3Cp2IGXBPfYeov5hTabPdJGP2qxMJW7kGMpxCuruM4)

   Amazing progress `Proud of you 👏🏻`

**Type 2 - Public Links:**

Now this is the easy type of links, choose a link of your liking. In my case I’ll copy the google URL `https://www.google.com/`, and do the same thing with the `<a>`

```html
<a href="https://www.google.com/">Go to Google</a>
```

To get this on our page:

![img](https://lh3.googleusercontent.com/9sYBCnxEoCYj9PmO89z_RUQO-tGpuvVs6ayakjsOul0MAfXEdUBCirRhopjksEQTv8yylgjctF_C2g-nU5RhTEatBekcfhpsWFmpmna25xZo5bu6E-zKMU8bTmL5xDHyRxbzaNIg)

**03_New_Line**

Did you catch something in this result?

![img](https://lh4.googleusercontent.com/UXyr6ebC0VQlgJVYFaRpVB23lftKI9RLQBonxjwWpTIAHBen1idDa2LW53o3rLP1Ax9s-DzApb8OGr6xMRRf_aXO5r5Bs8e57FjLjvSR5ytuahi4vVh5A7KSxLShZHzG6-ZP_uNn)

The thing is that everything is next to each other 👀, this brings us to the smallest tag which is `<br>` . We will use `<br>` between the things we need a new line in them.Our code will look like this:

```html
<body>
  <h2>Caesar Salad Recipe</h2>
  <p>Simple salad that can be done in 15 minutes</p>
  <img src="images/salad.jpg" alt="salad image" height="120px" />
  <br />
  <img
    src="https://www.recipetineats.com/wp-content/uploads/2016/05/Caesar-Salad_7-SQ.jpg"
    alt="salad image"
    height="120px"
  />
  <br />
  <a href="steps.html">Click here</a>
  <br />
  <a href="https://www.google.com/">Go to Google</a>
</body>
```

Ready to see the page? 🥁🥁🥁🥁

![img](https://lh3.googleusercontent.com/KPzKQ0zAzrr2f3HWrWt1NuGux9PSr81xFXlm69Wu0yVtxBKb0rORI9zyxV5HMSXQ5wcJv9IZHb7IPNnGEGetZKRYouyzaI_ChXHe9fqUKrgQ6MYYzjwiB4kWIv03DBwA1brC-qyg)

**04_List**

Of course you are thinking about our second page? Don't worry I didn't forget about it😎We will use the second page to put the steps needed to do our recipe, in my case the for the cesar salad. Let us open the `steps.html` page, and put the `html:5` with removing `<meta>` to get a clean code:

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Cooking Steps</title>
  </head>
  <body></body>
</html>
```

Let us put some lists, we have two types of them:

**Unordered List:**

It is the lists that does not have numbers, my list will be:
Cheese
Lettuce
Chicken
Now let us implement it using tags:

```html
<ul>
  <li>Cheese</li>
  <li>Lettuce</li>
  <li>Chicken</li>
</ul>
```

This code will display:

![img](https://lh3.googleusercontent.com/GCr1xlmGekgH4WlRLyvBZz7UPgdxFrh8xouhtqAqZgWaVIt1rt4Rx5ohIHV6Jx_zt1SiwyJCM1vPFBVKfw5D6L8DfkEyS7vqhZsXsFsJJxuIcqfdv3MxWpu0IRoNYtWhW8NkK_nU)

📝 Note:

> `<ul>` : is short for unordered list
> `<li>`: is short for list item, all list items must be in the `<ul>` to be included in the list

**Ordered List:**

It is the lists that have numbers, my list will be:

1. Clean your vegetables

2. Cut the vegetables

3. Prepare a chicken and cut it

4. Put all ingredients in a bowl

5. Put your sauce

   Now let us use two tags:

```html
<body>
  <ol>
    <li>Clean your vegetables</li>
    <li>Cut the vegetables</li>
    <li>Prepare a chicken and cut it</li>
    <li>Put all ingredients in a bowl</li>
    <li>Put your sauce</li>
  </ol>
</body>
```

This code will display:

![img](https://lh3.googleusercontent.com/tU7k4bUDYHBx9akfP2BXI-cmbUEfv2cUD-QZii02TYe0CFxalQAeLvIK3M-9FWabIMLhjok4Fx06CUTBSBrVi6wFQwkVO9uvgIR44-FmZBrqByqAEF4kDiomIpcCRkywzCc2aSdP)

**📝 Note:**

> `<ol>` : is short for ordered list
> `<li>`: is short for list item, all list items must be in the `<ol>` to be included in the list. The same tag is being used for both lists.

**`steps.html` code:**

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Cooking Steps</title>
  </head>
  <body>
    <ul>
      <li>Cheese</li>
      <li>Lettuce</li>
      <li>Chicken</li>
    </ul>
    <ol>
      <li>Clean your vegetables</li>
      <li>Cut the vegetables</li>
      <li>Prepare a chicken and cut it</li>
      <li>Put all ingredients in a bowl</li>
      <li>Put your sauce</li>
    </ol>
  </body>
</html>
```

To make it better looking and understandable, `<h3>` with a simple description above each list will give us this result:

![img](https://lh5.googleusercontent.com/8kcwUDd1g9_Mf4JIfgtwqrHjadWz1EljNaJ7Kn_dOHicWvT-pin48La3cDvE5_M9YWoCrl7TCN0WqtZFgqs1i7f8uPxkM0FkuENoM_F7wnD-Asqx376Ub14E5Hq8YVKjHrVA8fli)
