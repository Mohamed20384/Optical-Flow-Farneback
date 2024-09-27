# Farneback Algorithm

Easy:
Imagine you have a flipbook! Each page is like a picture from a short video. The Farneback algorithm is a super detective that figures out how much stuff moved between the pages (frames) of your flipbook.

Here’s how it works:

Stacking Pictures: First, the detective makes a bunch of copies of each page, but shrinks them down — like a mini flipbook! This helps catch both big and tiny movements.
Color Guessing Game: On each page, the detective guesses how the colors of tiny dots might change if you flipped a few pages ahead. Imagine trying to predict if a red dot becomes a little pinker or a brighter red.
Finding the Perfect Shift: Then, the detective plays a game! It slides each dot a tiny bit left or right, checking every possibility. The goal is to find the exact slide that makes the predicted color in the first page match the actual color in the next page, like a perfect fit!
Putting it Together: Once the detective figures out the best slide for every dot on every page, it combines all the information. It uses the small pages (tiny movements) for details and the big pages (shrunk copies) for bigger movements. This creates a map showing how much and in which direction everything moved between the pages (frames) of your flipbook!
The Farneback algorithm is like this detective because:

Super Sleuth: It’s very good at figuring out exactly how much things moved (high accuracy).
Tough Challenges: It can handle even if the pictures are a little blurry or the lighting changes (robustness).
Big Moves, No Problem: It can track things that move a lot between pages (large displacement handling).
But there are some downsides too:

Slow Detective: It takes a while to check all those possibilities for every dot (computationally expensive).
Not for Live Action: It might take too long to work for super-fast flipbooks (not ideal for real-time).
Overall, the Farneback algorithm is a powerful tool that helps computers understand how things move in videos, which is useful for things like:

Following Action Heroes: Tracking characters as they run and jump in movies.
Fixing Shaky Videos: Making shaky phone videos smooth by understanding how the picture wobbled.
Finding Moving Objects: Separating cars from the background in a video by seeing which parts are moving the most.

![image](https://github.com/user-attachments/assets/1a1b150c-9d38-469b-90ff-be51b9b589e7)

Another easy example:
Imagine you’re watching a cartoon with your favorite character zooming across the screen! The Farneback algorithm is like a super-smart detective who figures out how fast and in what direction that character is moving.

Here’s how it works, like a step-by-step game:

Picture Pyramid: The algorithm first takes two pictures from the cartoon, like two frames showing your character moving. Then, it makes a special stack of pictures: one big one, one a bit smaller, and another even smaller, like a pyramid! This helps track both big movements (like jumps) and small movements (like wiggling ears).
Color Guessing Game: On each picture in the pyramid, the detective guesses how the colors of tiny spots might change between the two cartoon frames. Imagine the detective saying, “This red dot here, maybe it’ll be a little to the left and slightly brighter in the next picture?”
Finding the Best Match: Now comes the fun part! The detective checks all these guesses for each spot. It’s like trying out puzzle pieces to see which ones fit best. The detective keeps changing the guesses until they match the actual colors in the second picture as closely as possible.
Putting it All Together: Once the detective has figured out the best guess (movement) for each tiny spot in all the pyramid pictures, it combines this information to create a big picture — a “movement map” showing exactly how fast and where everything in the cartoon moved!
This “movement map” is super helpful for computers because it lets them understand what’s happening in videos. They can use it to:

Follow Cool Characters: Track how your favorite characters move from frame to frame in a cartoon.
Fix Shaky Videos: Smooth out videos that are a bit wobbly by understanding how things are actually moving.
Separate Objects: Figure out which parts of a video show one thing and which parts show another, like telling the difference between a moving car and a waving flag!
While the Farneback algorithm is super clever, it can be a bit slow sometimes, just like solving a complex puzzle. But overall, it’s a great tool for computers to understand the exciting world of moving pictures!

This algorithm is pretty clever because it looks at the pictures in different levels, like zooming in and out. It helps it find the movements that are really big and the tiny little movements too. But it’s not perfect and sometimes it might get confused in places where the picture has lots of details or the lighting changes.

We can use this movement information for lots of fun things. Imagine tracking your favorite cartoon character as it runs around or even helping a robot understand what’s happening in the world. The Farneback Algorithm is a helpful tool to understand movements and make sense of the exciting things happening in our pictures and videos!

![image](https://github.com/user-attachments/assets/c53959ec-4f48-4039-a19e-d78e1cd19a4f)

Applications of Farneback Algorithm

The Farneback algorithm is known for its high accuracy and robustness, making it valuable in various computer vision applications, including:

Motion Tracking: Following the movement of objects in videos, such as people or vehicles.
Video Stabilization: Removing unwanted camera shake from footage.
Object Segmentation: Identifying and separating objects from the background based on their motion.

Advantages:
1. High accuracy in optical flow estimation.
2. Robust to noise and illumination changes.
3. Handles large displacements between frames.


Disadvantages:
1. Computationally expensive compared to some simpler methods.
2. May not be suitable for real-time applications due to computational demands.

## Output 
![image](https://github.com/user-attachments/assets/a10fe566-85e8-4f63-a219-a9ef5b6c53f1)

![image](https://github.com/user-attachments/assets/c3ab3d15-041c-4e9a-8f9e-0312144c1d5b)
