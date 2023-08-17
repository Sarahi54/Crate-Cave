# Crate-Cave
Crate training for your pet (PP1)

Crate-Cave is a website designed to assist first-time dog owners in setting up a routine and structure for their new furry family members. The site will provide a guide and information on why crate training is beneficial, regardless of whether or not they are first-time pet owners. Crate-Cave is also meant to inform pet owners about why crate training can also help their pets adjust to their new home and space , by helping them build a safe area for their dogs.

![mockup generator](/assets/images/website-mockup.png "screenshot of mockup generator")

FEATURES:

∙Navigation
The navigation bar will have three sections, making it easy for the user to navigate through the internal links on the Crate-Cave website.

This section of the website will include the full responsive links to the following tabs:
 *Home: where the user will find reasoning on why crate training may be helpful
 *How to Crate Train: where the user may find the methods on how to crate train
 *Signup: the page where the user may sign up to receive newsletters.

![NavigationBar](/assets/images/nav-bar.png "navigationbar")

UX/UI Section:
● Site Goals : Inform user about why crate training is positive for dogs despite the negative stigma related to crates.
● Design Choices, For heading font Oswald was used and overall font for the page is Roboto. Scroll down website easy to use that included internal links on navigation bar.
● User stories
-As a User: they go into the website and can easily find information about the postivity behind crate training and how to get started.
-As a site Administrator: the website is clear and straight to the point. Easy to manoeuvre through it.

-Ethos Section:
Why is Crate training important?
1. Step 1: Choose the Right Crate for Your Dog
there are three main types of crates to choose from – metal, plastic and fabric. What you choose depends on your puppy’s preferences and the primary purpose of the crate. If you often travel in the car with your puppy, for example, you’ll probably want something quite lightweight but safe.It’s important, she notes, that you don’t buy a crate that is too big for your dog.It needs to be large enough for your dog to stand up in, turn around and lie down comfortably.
2. Step 2: Let your dog explore the crate
You want to make sure the door is open and should never force your dog into the crate. It’s fine to gently encourage exploration and treats can come in handy here. Never force your pet into the crate as this can cause negative relations to it. 
3. Step 3: Build up the time your dog is in the crate
Once your puppy is starting to get accustomed to their crate, you will want to start slowly building up the amount of time they’re in there. A good way of doing this is to feed them in their crate.Once you think that your puppy is getting used to being in their crate, you can start shutting the door. It’s important you take this very gradually, only shutting the door for the briefest amount of time at first and opening it again if your puppy shows any signs of wanting to get out.

4. Step 4: Leaving your dog in the crate
Your dog needs time outside the crate to play, eat, and use the bathroom. Dogs don’t want to soil where they sleep, but if there’s too long of a stretch without a walk, they might end up doing so. Once your dog get accustomed and feels safe in their crate start increasing there time in small steps. Remember Adult dogs shouldn't be left in crates for more than 6-8 hours. Puppies of 17 weeks and older can handle up to 4 or 5 hours in a crate at a time.

-The Footer:
Here I've included the links to our social media pages available with the media logos.

![Footer-image-social-media](/assets/images/footer.png "Social-Media-Links")


 Sign up Page:
The sign up sections allows users to register with first name, last name and email. Submit button has been added to box. Included friendly inviting background image.

![Signup-box](/assets/images/signup-section.png "signup box with background")


TESTING:

-Validator Testing:
 * HTML
   - No errors were returned when passing through the official W3C validator
 * CSS
   - No errors were found when passing through the official (Jigsaw) validator
 * Accessibillity
   - Based on lighthouse results I can confirm that the colors and font are easy to read. Based on size of images lighthouse performance score was listed as 77. 

![lighthouse score](/assets/images/lighthouse-test.png "screenshot of lighthouse test")

Tested social media links located in the footer each link was clicked and new tab was opened with its oficial website corresponding to social media logo. 

![Footer-image-social-media](/assets/images/footer.png "Social-Media-Links")

Successfully tested sign up portal and was able to submit without issue. Also tested required fields successfully.

![signup-submit](/assets/images/signup-submit.png "tested signup portal")


Debugging:

When completing the website deployment from github the css code was not displaying on the live website. After looking at the HTML code I identified the problem and implemented a soloution. The root cause was that I failed to place the absolute file path for the internal links shown in the picture below.

![absolute path change](/assets/images/absolutepaths.png "screenshot of new code")


-Unfixed Bugs:
I initially created my website by graceful degradation. Unfortinatly due to my misjudged time management I was unable to create the correct media code for mobile devices. As seen on the mockup generator the website works for tablets,laptops and desktops succesfully, but the club-ethos section is not fully visable on a mobile device.
![heading](/assets/images/mobile-device-heading.png "mobile-device-heading")
![ethos section](/assets/images/mobile-device-ethos.png "mobile-device-ethos")
![main section](/assets/images/mobile-device-howtocratetrain.png "mobile-device-main")
![signup section](/assets/images/mobile-device-signup.png "mobile-device-signup")


Deployment:
![Deployment](/assets/images/deployment-display.png "screenshot of github")
The steps to deploy are as follows: 
In the GitHub repository, navigate to the Settings tab, From there go into the Pages tab on left side, select the Main Branch Once the main branch has been selected, refresh the page after a few minutes and a display with site url will appear at top of page. The live link can be found here - https://sarahi54.github.io/Crate-Cave/

Credits:

-Content:

- Used Social Media code from Love Running Project in order to display logos and links.
- Alot of the structure of my PP1 came from the Love Running Project guide, such as my Ethos-club section. I used similar structure learned from my Love Running project.


-Media:
https://unsplash.com for dog pictures
https://fonts.google.com for font options which were Oswald and Roboto
https://www.akc.org used as refrence for crate training guide
https://www.uk.pedigree.com used as refrence for crate training guide 




