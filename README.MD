Logic for HW-WireFrame Homework

Create Index.html
Create !DOCTYPE
add opening and closing html,head, body
create title with in head
Created Skeleton in body by adding 
        header, 
        nav, 
        section(with an H3)
        aside(with an H3)
        footer(with an H3)
with in section I added 
            article 
with in <article> I added 
            h1 with an H1 header
            p 
            
  *I did not use divs, or add class or Id's. I felt that in this scenerio to keep my css code clean and simple
  I was able to call the tag to get my page to be set up the way I needed           
            
            
created style css
linked style css to html (  <link rel="stylesheet" href="style.css" />  )
wrote * {} to make sure both padding and boarder to elements are consistent throughout the page
wrote the code for
            Body (as per the specification on the homework assignment)
                added margin: 0 (top and bottom) auto (left and right)  for all element in the body section
                    

Tag and wrote code for 
Header 
                     height and padding to create it size and space
                     margin-bottom to but room between header and Nav
Nav
            height and padding to create it size and space
            margin-bottom to but room between header and Section/Aside
            
Section
            Position absolute; to poistion it underneath the nav (its 1st position ancestor)
            width (as per the specification on the homework assignment)
            padding to create space
            margin bottom to give space between room between section and footer
        
Article, H1, P
            used width at 100% to fit the rest of the available space (based on the padding,
            margin, of section)
            padding to give space between it self and section (or h1/p from article)
            
Aside 
            Position Relative to keep it relative to its position (after section/before footer)
            float right; to have keep it to the right side of the body
            width of 445 is the difference of 960 (body width), 495 (section width), and  padding of 20
            height at 335 to make it match how long section was
            
footer
        padding for size and space
        clear both to prevent it from moving above/in front of section and aside
        
            
            
            
