# **let make a 3D printable ruler together!**

hello im William! 

Ive put together what i hope is a follow-able guide on how to make a ruler in fusion 360

there should also be an onshape guide releasing 

Good luck and have fun!




---
**Note for CAD nerds: **

I know there will people saying [insert-cad-here] is better and whatnot, however fusion is what im most comfortable with , if youre more familiar with other CAD software youre more than welcome to use that. Im not saying fusion is the perfect or the best, because its neither.
But even if you do know other CAD , why not try something new, try fusion :3 


# 1). an introduction

**A quick pic of what we are trying to make**

![DSC50000-347](https://github.com/user-attachments/assets/671ef482-5fce-4c28-94b9-5f2684285427)

this is just a plain ruler, most rullers will start off looking something like that, however i encourage and expect that you will customise them to your hearts content to make your ruler uniquely yours :3




## Fusion 360 UI

hopefully your fusion360 looks something like this
<img width="2514" height="1208" alt="image" src="https://github.com/user-attachments/assets/3fe5b671-ccde-46fb-a34b-4657f6b16c87" />
all the tools we will be using to draw sketches and turn those sketches into 3D things should all be at the top of the screen

**my favoruite keybind**
s - search
<img width="724" height="439" alt="image" src="https://github.com/user-attachments/assets/e948c10d-9b12-437d-89c9-a60ad9c4f8bd" />

if you ever get stuck because i say something and you just cant find it , this keybind is a life saver.

its also cool because if youre looking for a feature in fusion you can just type in the name and see if it exists


**Keybinds for moving arround your model:**

pan - hold middle mouse buttom
zoom - scroll mouse wheel
orbit - hold shift + middle clicke + mouse buttom




**IMPORTANT NOTE:**
**unlike onshape, fusion does not auto save, make sure you regularly save to avoid accidents**

and like almost all software
save - ctrl+S 




# 2). beginings of the ruler

now for making the ruler
the max size of ruler we can print for you is:
### 200mm long , 70mm wide, 4mm tall
(i made it big so you dont skip past it)
so please keep your maximum dimensions below that







We want to start by drawing out an overhead outline of out ruler
![_DSC2267](https://github.com/user-attachments/assets/ca7f1040-3068-4fc7-ab95-b10ee664e16e)

<img width="1919" height="1177" alt="image" src="https://github.com/user-attachments/assets/f51ba94f-7f8a-49c0-84e3-379ff05b2cc4" />

then we need to select a plane to start drawing on 
you can click any of the orange squares and it will work

your screen should look something like this
<img width="1919" height="1177" alt="image" src="https://github.com/user-attachments/assets/8f7153ef-34c5-4cc3-8ec0-5ebb261cb168" />

now we can use the 2 point rectangle tool to draw a rectangle that will define how big our ruler is!
<img width="1919" height="1176" alt="image" src="https://github.com/user-attachments/assets/d9e713d4-4cc2-4485-87b7-3345cfa5112b" />

with the 2 point rectangle tool:
- you click on the canvas to start or stop drawing
- you can type in numbers to set the size
  - you press tab to switch between them

your ruler should look something like this
<img width="1919" height="1199" alt="image" src="https://github.com/user-attachments/assets/9d402ac1-5254-4a66-9bc4-6d9b2e94ba19" />

now we can press finish sketch to finish the sketch
<img width="1919" height="1174" alt="image" src="https://github.com/user-attachments/assets/82a551f1-e613-4f66-b2ad-db62b8dc8c3a" />

next we want to make the 2d drawing into the start of our 3d ruler
to do this we use the extrude tool
you can either click the icon
<img width="43" height="59" alt="image" src="https://github.com/user-attachments/assets/67815310-567a-468c-9251-46e1a6b78b27" />

or use the shortcut - e 

because we only have one sketch it has probably auto selected it
but if not

in the extrude pop up, click on profiles
and then click the filled in bit of the ruler we just drew

now we can extrude it the distance we want by setting the distance number in the extrude tab
im going to make my ruler 3mm thick

so you should be here
<img width="1919" height="1176" alt="image" src="https://github.com/user-attachments/assets/0bb1c539-53fb-469e-8aec-1ef5bce51c77" />

and you can press ok now

well done! 
youve made the start for our ruler

# 3). adding the gradations

dont be scared by the word gradations, its not some fancy fusion thing, its just the name for the marks on a ruler. 


to do this we are going to draw and make one mark
and then use the "rectangular pattern" tool to copy it accross the ruler without drawing it a bunch


### how big to make the gradations?
gradations smaller than 1mm probably wont print due to the 0.4mm nozzles that are common on 3d printers

the back ruler has 5mm spacings
the closer one has 1mm spacings
personally i thinkt the 5mm ones are clearer to read 
![_DSC2270](https://github.com/user-attachments/assets/da2270f6-fc01-45d6-b147-9bd4539d4304)


a closer up pic of the 1mm gradation ruler
![_DSC2269-2](https://github.com/user-attachments/assets/d8f0afbd-0915-424a-b7a4-50ebd5d00f9d)


for my ruler i want short marks every 5mm
and big marks every 10mm

so lets start on the smaller ones

we want to start by making 1 mark in the ruler

to do that we new to draw a sketch of what the marks look like
<img width="1919" height="1147" alt="image" src="https://github.com/user-attachments/assets/26fd2715-9ef7-4335-9bcd-d54ae11c7d27" />
so we click the new sketch button
and click the top of our ruler where we want the mark

my prefered method for doing it goes something like this
<img width="1918" height="1147" alt="image" src="https://github.com/user-attachments/assets/018d1652-bd21-467c-96da-f17466deceb9" />
drawing a line how far apart the marks should be from the edge
so for me 5mm

i want my markings to be 5mm long, and 0.4mm wide
i also want them to be centred on the point we just marked

so we can draw a two 0.2mm x 5mm rectangle on either side

next we finish the sketch
and then extrude into the ruler to make the marking! :yay:

<img width="1919" height="1178" alt="image" src="https://github.com/user-attachments/assets/7f077ba6-e1b4-49ac-b2a5-36636924a70c" />

<img width="1919" height="1170" alt="image" src="https://github.com/user-attachments/assets/349580c7-5508-4ddd-b30e-bf666dfdab2b" />
like this!
<img width="1917" height="1175" alt="image" src="https://github.com/user-attachments/assets/4654bc43-315d-487d-b4c2-b242da0fc359" />

now we are going to use a pattern to make the pattern continue down the ruler!
<img width="1916" height="1176" alt="image" src="https://github.com/user-attachments/assets/65891933-f245-4e8a-a5f7-a6391c0e7c7e" />

we are trying to pattern the cut we made, which is a feature
so we need to change from bodies to feature
<img width="1919" height="1068" alt="image" src="https://github.com/user-attachments/assets/6e00af2b-ffca-495f-a50b-9a87d8ec5426" />
<img width="258" height="194" alt="image" src="https://github.com/user-attachments/assets/1b68468f-8836-42f8-9914-62ff2d45e4fa" />

now we need to select the feature
to do this we can either try hover over the indent and hope it works
or 
we can click the extrude feature we made in the time line (i prefer this method)

<img width="1919" height="1175" alt="image" src="https://github.com/user-attachments/assets/00b7c656-4b8e-4206-8592-651d153c355a" />

next we next to pick the "axis" this is just the direction that fusion makes the pattern in
we can just pick the long edge of the ruler

<img width="1914" height="1174" alt="image" src="https://github.com/user-attachments/assets/071a856e-ee26-43be-a03d-2377b2be61c3" />

now we also want to change the mode from extent to spacing
and set the distance to how often we want the markings
i want them to be 5mm apart so i put 5mm in

<img width="236" height="553" alt="image" src="https://github.com/user-attachments/assets/037ade76-efbc-466e-9bb7-172ae4d22c0a" />

<img width="1915" height="1069" alt="image" src="https://github.com/user-attachments/assets/c13902ce-cb05-46e2-b15f-4f1a356d5f94" />
now we can see a preview

we just need to increase the quantity, 
<img width="1919" height="1179" alt="image" src="https://github.com/user-attachments/assets/9f70dfd7-c4b3-4a20-bd74-2b998e71aab1" />
boop
now we have the markings :yay:

<img width="1919" height="1177" alt="image" src="https://github.com/user-attachments/assets/d26f7833-6e5c-4cb4-b8ef-adc377aaa356" />

---
we  can repeat that process for centimeter markings 

if you did simple rectanlge marking like i did
you could just extrude every other one deeper
<img width="1919" height="1173" alt="image" src="https://github.com/user-attachments/assets/15e55195-83c3-4bdb-951a-1708519fbdb6" />
<img width="1919" height="1179" alt="image" src="https://github.com/user-attachments/assets/fe09b1be-66d9-408e-815b-cbfd75a0fa7f" />

the other way would be repeating the process for the first markings, but you make them bigger / a different shape , and set the spacing to 

# 4). adding the numbers (optional)

time to add numbers!
if you want numbers that is.
you dont need to add numbers, if you want the extra space for customising it the way you want feel free to leave them out.

so first we are going to create a new sketch on the top of the ruler again
<img width="1919" height="1176" alt="image" src="https://github.com/user-attachments/assets/f9d99d69-9cba-463d-a9a9-d7cff6baa036" />

then we can use the line tool to draw out a box where we want our numbers to be (the number dont need to fill up the box)
<img width="1919" height="1156" alt="image" src="https://github.com/user-attachments/assets/1df2605f-69a6-4a8d-a71a-b9d40d3d42fc" />

i made the lines into "construction" lines
which just means that, you can snap onto them , and use them to construct things. but they wont affect which parts a filled in i think the term is "non-printing"
<img width="1919" height="1176" alt="image" src="https://github.com/user-attachments/assets/0ca73688-7e69-49ec-a535-37c202c3d93a" />

then we can use the pattern tool to put one above each marking where we want a text box
<img width="1919" height="1171" alt="image" src="https://github.com/user-attachments/assets/10d61704-4f76-4ad3-80ac-af1e3f820d41" />
you could draw them out by hand
but i dont think either of us fancy drawing out 15 boxes

so we select all the lines that we want in the pattern
<img width="1910" height="1169" alt="image" src="https://github.com/user-attachments/assets/3b18b435-ebf4-45cd-868e-d2e6b33a6a3a" />

we pick a direction
<img width="1919" height="1065" alt="image" src="https://github.com/user-attachments/assets/eededb1f-0a9a-4806-86bb-9b94cce26292" />

<img width="1919" height="1173" alt="image" src="https://github.com/user-attachments/assets/47dad7ee-e273-470c-9ae7-af66df1d010b" />
and thats the boxes in there
<img width="1558" height="467" alt="image" src="https://github.com/user-attachments/assets/ac894583-e52f-4d7f-9a69-c897bd7d207e" />

next we have to add the text

<img width="1913" height="1175" alt="image" src="https://github.com/user-attachments/assets/a4d25416-321d-455c-ae96-6937ab312e77" />

so now we have a box which we can click in two places to define the corners
<img width="334" height="283" alt="image" src="https://github.com/user-attachments/assets/a2994e64-156e-4b38-bebb-49a936b1e528" />

I let it snap onto two oposite corners in the first box

and i type 1 into the window on the right
<img width="1904" height="1149" alt="image" src="https://github.com/user-attachments/assets/b66f0a51-f40c-4293-9b73-5c9f96ae65d0" />

its also worth considering what size you make your font now
because if you have double digit ammount of units
make sure you have space for that in the text boxes

i also picked align centre  for horizontal and vertical

so a font size like this will clearly overlap with the next letter
<img width="1419" height="960" alt="image" src="https://github.com/user-attachments/assets/8d4f44bc-5fe5-463c-a50b-61d3e1e6d445" />

but a font like this should be ok
<img width="1829" height="1141" alt="image" src="https://github.com/user-attachments/assets/3998bce9-0040-415a-a900-07a7f586ebb4" />


a bit of clicking later you should have something like this
<img width="1919" height="1174" alt="image" src="https://github.com/user-attachments/assets/74c8e5c6-4c41-4ae4-bcb5-3a3c42065a05" />


---

<img width="1919" height="1180" alt="image" src="https://github.com/user-attachments/assets/805cd3b0-71ed-42bc-9576-3bddbbc1f3ae" />

hopefully you are at a point that looks something like this!

---










# finish adding the rest of ruler
---


---
Now you should have a ruler!
however youre not quite done yet
for the next part your on your own

the last part of this is customising your ruler

**here are some ideas:**
- perhaps make it a cool shape, in the first step we made our ruler a rectangle, why not make one of the sides wavy
- different shaped gradation makes on the ruler
  - instead of the little line i used , perhaps a triangle, or whatever else you can come up with
- crazy units?  Cubit, Smoots, Links, Light-nanosecond etc
- add a cool pattern
  - perhaps hexagon cuttouts
  - stripes on it cut into it
- perhaps you want to add some text on it with the text tool
- add graphics
  - you can import SVGs into sketches, so you could draw an orph, convert it to an SVG, and have and orph ruler
  - **if you add art it has to be yours**
  - **AI "art" is strictly prohibited**

and if youre struggling to do something, give it a google search, there are plenty of amazing youtube tutorials and forums out there with guides on how to do everything under the sun!

**Example photos**


example of different shaped tick pattern
<img width="1353" height="705" alt="image" src="https://github.com/user-attachments/assets/5d105ce4-b3ec-4c26-b8eb-e56b8297891e" />

neocat ruler, example of being able to add art
fusion has an import SVG function that helps with this 
<img width="1321" height="712" alt="image" src="https://github.com/user-attachments/assets/a582d9d7-d8c7-4ab7-9c2a-7a1081d23b07" />

example of some things you could do to the edge of the ruler
<img width="1332" height="624" alt="image" src="https://github.com/user-attachments/assets/6a6183d3-eff7-490d-8be8-0ceab97dde98" />

a cool wavy pattern in the ruler
i just clicked arround with "split point spline" in the sketch to make it, looking forward to the cool things you guys come up with!
<img width="1585" height="719" alt="image" src="https://github.com/user-attachments/assets/cb6e2c0d-ccba-42cf-b1f9-e4e7ac208e2d" />










