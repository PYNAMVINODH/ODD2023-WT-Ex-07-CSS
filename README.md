# Ex-07-CSS
# Name: PYNAM VINODH
# Ref.no:212223240131
# Aim:
# Ex-7(i):

Using CSS media queries, modify the webpage's color scheme with the following requirements:

Default Color Scheme: Background color: Light gray (#f4f4f4) Text color: Dark gray (#333) Link color: Blue (#007bff) Small Screen Adaptation (Max-width: 600px):

Change the background color to dark gray (#333) Change the text color to light gray (#f4f4f4) Change the link color to light green (#28a745)

Dark Mode Preference:

If the user has set their device to dark mode, override the above styles with the following: Background color: Black (#000) Text color: White (#fff) Link color: Cyan (#17a2b8)
# Steps:

## Step1:
Meet the requirements for the default mode or light mode
## Step2:
Choose a device which is smaller in size of mobilephone of 600px and meet the prefered requirements
## Step3:
Meet the requirements for the prefered darker mode

# Code:
media.html:
```
 <!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <style type="text/css">
            body{
                    font-size: 50px;
                    color: #333;
                    background-color: #f4f4f4;
             }

             p {
                   font-size: 35px;  
                   text-align: center;
            }
            a{
                font-size:35px;
            }

           a{
              color: #007bff;
           }
                 @media (max-width: 600px) {
                        body {
                            background-color: #333;
                            color: #f4f4f4;
                            a {
                                color: #28a745;
                           }
                        }
                    
                    }

                  @media (prefers-color-scheme: dark) {
                        body{
                                font-size: 50px;
                                background: #333;
                                color: white;
                            }
                         a {
                             color: #17a2b8; 
                         }
                     }

                    footer {
                        font-size: x-large;
                    }
           
        </style>
    </head>
    <body>
        <fieldset>
            <p style="text-align:center"> 
                <p style="text-align:center"><b>CSS Media Queries</b></p>
                <p style="text-align:center"> 1.webpage's color scheme</p>
            </p>
        </fieldset>    
        <hr>
        <a href="https://github.com/Karthi-Govindharaju/ODD2023-WT-Ex-07-CSS.git">https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS.git</a>  
        <footer>~created by PYNAM VINODH</footer>
    </body>
</html> 
 

```
 




# Output(i):
light mode:
![Screenshot 2023-12-15 192239](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/dfda72f1-d09d-44b7-b0c7-ec6a0219ab58)







Dark mode:
 ![Screenshot 2023-12-15 191852](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/e74d2d52-592d-414d-b868-e9b7198f6668)




Smaller screen:
 ![Screenshot 2023-12-15 193329](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/cb935be4-5039-4026-a73e-35752d9181f6)

# Ex-7(ii):
## Aim: To use a media query in CSS to apply different styles to a webpage for mobile devices (with widths less than 600px) and desktop devices (with widths greater than or equal to 600px) by providing an example CSS snippet to demonstrate your answer.
## Step 1:
Start a html project
## Step 2:
Create a css file in the same folder in which html file is created
## Step 3:
inside html code give href link of the css code
## Step 4:
meet the requirements given in the question
## Step 5:
run the program with prefered screen width
# Program:
```
2.style
 <style type="text/css">
            body{
                    font-size: 50px;
                    color: #333;
                    background-color: #f4f4f4;
             }

             p {
                   font-size: 35px;  
                   text-align: center;
            }
            a{
                font-size:35px;
            }

           a{
              color: #007bff;
           }
                 @media (max-width: 600px) {
                        body {
                            background-color: #333;
                            color: #f4f4f4;
                            a {
                                color: #28a745;
                           }
                        }
                    
                    }

                  @media (prefers-color-scheme: dark) {
                        body{
                                font-size: 50px;
                                background: #333;
                                color: white;
                            }
                         a {
                             color: #17a2b8; 
                         }
                     }

                    footer {
                        font-size: x-large;
                    }
           
        </style>
```
# Output(ii):
default:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/8e8d1ed9-0cd8-4bc7-a8fe-724c460c045b)

max screen width of 600px:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/d8f03ed6-8e7b-4c2f-bbb6-1cfe564ea08e)


# Ex-7(iii):
## Aim:Explain how you can use CSS media queries to apply different styles based on the orientation (landscape or portrait) of the device. Provide a CSS example where you change the background color of the body based on the orientation.

## Step1:
start a html project
## Step 2:
create a css file in the same folder in which file is created,give the href link in the html code
## Step3:
Define a CSS media query for each orientation. The syntax for a media query is @media (orientation: value), where value can be either portrait or landscape.
## Step 4:
You can change background color of it
## Step4:
Run the html program
# Program
```

3.style
<style type="text/css">
           @media (orientation: potrait) {
                        body {
                                background-color: white;
                                color: black;
                                a {
                                    color: red;
                                }   
                        }
             }
                        @media (orientation: landscape) {
                                    body {
                                        color: #28a745;
                                        background-color: rgb(114, 47, 80);

                                        a {
                                            color:violet;
                                        }
                                    }
        
                          }

             p {
                   font-size: 35px;  
                   text-align: center;
            }
                a{
                    font-size:35px;
                }
                    footer {
                        font-size: x-large;
                    }
           
        </style>
```
# Output:
landscape:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/70df04a5-9a9b-410d-9d45-65f0b257e55c)

potrait:
![Screenshot 2023-12-18 085716](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/b8c52976-b32e-4d6f-ab2d-22b26750d6a2)

## Ex-7(iv):
## Aim:To describe how you would use media queries to adjust typography (like font size and line spacing) on a website to improve readability across different device sizes, from mobile phones to large desktop monitors. Include a CSS code snippet in your explanation.
## Step1:
start a html project
## Step 2:
create a css file in the same folder in which file is created,give the href link in html code
## Step 3:
give different font sizes for different screen sizes accordingly
## Step4:
adjusting different colors for different screen width
# Step5:
Run the html program
# Program:
```
4.style
  <style type="text/css">
          body {
                font-size: 20px;
                color: yellow;
                background-color: purple;
            }

                    a {
                        color: yellow;
                    }
                    .non-essential {  
                           display: none;
                        }
                    @media (min-width: 600px) {
                                body {
                                    font-size: 50px;
                                    background-color: pink;
                                    color: #f4f4f4;
                                    a {
                                        color: #28a745;           
                                    }
                                 }
                      }
                            @media (min-width: 800px) {
                                        body {
                                                font-size: 80px;
                                                background-color: violet;
                                                color: #f4f4f4;
                                            a {
                                                color: #28a745;          
                                            }
                                        }
                                }
                                    p {
                                        font-size: 35px;  
                                        text-align: center;
                                    }
                                        a{
                                            font-size:35px;
                                        }
                                            footer {
                                                font-size: x-large;
                                            }
           
        </style>
```
# Output(iv):
min-width=800px:
![Screenshot 2023-12-18 090921](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/30a2e8bf-d97d-400b-a22e-33ecffb7333f)



max-width=600px:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/0a171708-32e1-444b-a253-fdb9800f2dbb)





default:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/470ad5ed-4845-4f90-8bbf-fcd193a46e8b)


# Ex-7(v):
# Aim:Media queries can be used to provide print-friendly styles for web pages. How would you use a media query to change the styling of a webpage when it is printed, such as changing the background to white and hiding non-essential elements Provide a CSS example.
## Step1:
start a html project
## Step 2:
create a css file in the same folder in which file is created,give href link in html program
## Step3:
after creating a css file give Inside each media query block, adjust the styles for the identified elements. You can change the background to white and hide non-essential elements.
## Step4:
test the html file
## Step5:
run the html program
# Program:
```
5.style
 <style type="text/css">
           body {
                    font-size: 50px;
                    color: #333;
                    background-color: #f4f4f4;
            }

                a {
                    color: #007bff;
                }
                    @media print {
                                body {
                                        font-size: 20px;
                                        background-color: #333;
                                        color: #f4f4f4;
                                                a {
                                                    color: #28a745;
                                                            .non-essential {
                                                                    display: none;
                                                                }
                                                }
                                  }
                            
                        }
             p {
                 font-size: 35px;  
                 text-align: center;
            }
                a{
                    font-size:35px;
                }
                    footer {
                        font-size: x-large;
                    }
           
        </style>
```
# Output(v):
default:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/a6f303c9-452c-434b-b114-9c3d9552c824)

non essential:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/f665182e-d83a-42ca-a164-9445996862e7)

# Ex-7(vi):
# Aim:With the increasing popularity of dark mode in user interfaces, explain how you would use a media query to detect if the user has set their system to prefer a dark color scheme. Provide an example of how you would change the background and text colors of a website based on this preference.
## Step1:
start a html project
## Step 2:
create a css file in the same folder in which file is created,give href link in html program
## Step 3:
using media queries set the preference to dark mode and night mode
## Step 4:
change the background color and font color to different
## Step 5:
run the html program
# Program:
```
6.style
        <style type="text/css">
          body {
                font-size: 50px;
                color: #333;
                background-color: #f4f4f4;
            }

                a {
                    color: #007bff;
                }
                    @media (prefers-color-scheme: dark) {
                                body {
                                    font-size: 50px;
                                    background: #333;
                                    color: white;
                                }
                                    a {
                                            color: #17a2b8; 
                                    }
                    }
                                    p {
                                        font-size: 35px;  
                                        text-align: center;
                                    }
                                        a{
                                            font-size:35px;
                                        }
                                            footer {
                                                font-size: x-large;
                                            }
           
        </style>

```
# Output(vi):
lightmode:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/3395dc0b-dbc3-46ab-9a50-b52fa9ef96f1)



darkmode:
![image](https://github.com/PYNAMVINODH/ODD2023-WT-Ex-07-CSS/assets/145742678/e56e8b9c-6ebe-440f-ba85-bd854ac3f112)













