# spotifyapp
Ever wonder how streamers display what spotify song they're listening to on stream? well here's a thing that does exactly that...



# Step 1, getting the ID and Secret:

Firstly, you're gonna wanna head [here](https://developer.spotify.com/dashboard/login) and login

after that, you need to create an app


![image](https://user-images.githubusercontent.com/34391969/211055994-7b936aa3-633b-4536-b34f-8db3e699c9e8.png)


then BOOM, you have it; i'd reccomend saving these in a text file somewhere for later use


![image](https://user-images.githubusercontent.com/34391969/211056544-06f0ca76-e0d6-4b54-9108-b456e32f84c1.png)


and now we're on to 
# Step 2, initiating the client:

Alright so ive tried to simplify this AS Much AS i Possibly Could for all you peeps okay, though i am really bad at explaining so just try an follow...

Firstly, we're gonna download the file and place the folder on your desktop (it doesn't have to be desktop but thats just the easiest placec to get to it)

Now that's done we run the program, it's gonna ask you for that Client ID first so have that ready to copy-paste


![image](https://user-images.githubusercontent.com/34391969/211058891-f3f970e4-a82e-4d80-98d1-66b472d8d551.png)


And now it's gonna ask for your Secret, so let's copy paste that as well


![image](https://user-images.githubusercontent.com/34391969/211059103-9edf114e-8e30-4b98-8d36-d445a1e31108.png)


Finally it's gonna ask for a bot name, now this does not matter at all, this is just what it'll call itself when it starts working


![image](https://user-images.githubusercontent.com/34391969/211059421-e62ec23e-4183-4eeb-b166-bcd485ebf7ce.png)



and now it's doing it's thing


![image](https://user-images.githubusercontent.com/34391969/211059700-6b70296e-562d-4265-9574-8515fba2e8b7.png)


You should also notice that it created some extra files in this folder, dw about it too much bc these are needed i promise


![image](https://user-images.githubusercontent.com/34391969/211059937-2b66e156-f278-4bcd-ac40-ddc455cbbcd2.png)


# For Step 3, connecting it to stream
For this step just keep in mind that i use [Streamlabs OBS](https://streamlabs.com/desktop/download), but i thinnk it should be the same for [obs studio](https://obsproject.com/download) as well

## Adding the image:
now this is for the image art or albumn art of the song being displayed, just click Add Source


![image](https://user-images.githubusercontent.com/34391969/211062070-ae8c84c4-c663-4c0d-84c5-7afc9f75e3b9.png)


then Image and make sure to add a new source, you can name it whatever but for now im just calling it 'album'


![image](https://user-images.githubusercontent.com/34391969/211062481-ec007d03-a1a5-41d5-b50b-c6892102debe.png)


after you add that, we need to search for the image that's in the files folder


![image](https://user-images.githubusercontent.com/34391969/211072814-d123a2e9-861e-4686-93f6-8d60fe44e50f.png)

and done, now for the text we do the same thing, but a little differently

Add the source and select the Text option, for me it's this


![image](https://user-images.githubusercontent.com/34391969/211073487-18d95f57-9257-4303-b454-cfea2f15f077.png)


just like the albumn, we're gonna be adding a new source instead


![image](https://user-images.githubusercontent.com/34391969/211073670-9d0ecbd4-4dc6-4258-b6cf-6be89ae36e0a.png)


after that, you can edit the font and size and such, but the important part on this one is that we select 'Read from file'


![image](https://user-images.githubusercontent.com/34391969/211073997-d40741b1-b668-466c-9038-e6c7d0d12248.png)


and now we have this product . . . enjoy


![image](https://user-images.githubusercontent.com/34391969/211074383-9d7011bb-e593-43db-9258-c7ec3d7a7b89.png)


