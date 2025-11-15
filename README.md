# spotifyapp
Ever wonder how streamers display what spotify song they're listening to on stream? well here's a thing that does exactly that...

//updated version for v3.0.1

# Step 1, getting the ID and Secret:

Firstly, you're gonna wanna head [here](https://developer.spotify.com/dashboard/login) and login

after that, you need to create an app

![image](https://user-images.githubusercontent.com/34391969/211055994-7b936aa3-633b-4536-b34f-8db3e699c9e8.png)


then BOOM, you have it; i'd reccomend saving these in a text file somewhere for later use


![image](https://user-images.githubusercontent.com/34391969/211056544-06f0ca76-e0d6-4b54-9108-b456e32f84c1.png)


//this is all the same ^

and now we're on to 
# Step 2, initiating the client:

Alright so ive tried to simplify this AS Much AS i Possibly Could for all you peeps okay, though i am really bad at explaining so just try an follow...

Firstly, we're gonna download the file and place the folder on your desktop (it doesn't have to be desktop but thats just the easiest placec to get to it)

Now that's done we run the program, it's gonna ask you for that Client ID first so have that ready to copy-paste

//ngl gang im lazy ash rn and i doubt anyone will even use this except me; BUT heres where the updates to v3.0.1 matter

//firstly that old console stuff i had here was ass; heres the updated:

//(yes the remember me works)

<img width="499" height="394" alt="image" src="https://github.com/user-attachments/assets/9aaa36fc-bd26-4e2e-a511-f3b6f4726f9d" />

//after you fill that out with all the info with the correct details and press the initiate client button; youll notice a pop up in whatever is your open/default browser for you to login to spotify

//and NO, it doesnt matter what you put there for bot name thats just display purposes, ANYWAY

//this is to get the 'access_token' we need to make the app run based off your account and what client id /secret you put in .... I.E this is pretty much making it lock to your account to show the music that you're listening to so dont worry about it and just login

//you'll notice that 2 things pop up now

<img width="498" height="395" alt="image" src="https://github.com/user-attachments/assets/fe09880b-3e18-43ce-9564-296c1af2434e" />

<img width="227" height="139" alt="image" src="https://github.com/user-attachments/assets/ff2767f3-8628-42fc-9dc9-4969b3e83a40" />

//the test button does literally nothing ; i only added it to make sure the console i added there was working and forgot to remove it ... its not that big a deal, like maybe 2 lines of code BUTT ill leave it for now

//As for the other one; if you accidentally close it don't worry (if you clicked the remember me anw) just click on reload client button and itll come back


# For Step 3, connecting it to stream
For this step just keep in mind that i use [Streamlabs OBS](https://streamlabs.com/desktop/download), but i thinnk it should be the same for [obs studio](https://obsproject.com/download) as well

//alr so this part is MEGA changed; instead of adding all those gay ahh files theres only 1

//add new window capture

<img width="898" height="697" alt="image" src="https://github.com/user-attachments/assets/76239021-4ec9-4909-918c-73b691f679d9" />

//name it whatever doesnt matter only u see it

<img width="594" height="318" alt="image" src="https://github.com/user-attachments/assets/d164dc5d-9456-45d0-a540-a70fad07c9c5" />

//[spotifyapp.exe]: Now Playing

//remove cursor 

<img width="597" height="797" alt="image" src="https://github.com/user-attachments/assets/abe5cc7d-032e-40d0-b114-4a40e940bfa2" />

//add and resize however you want

<img width="772" height="439" alt="image" src="https://github.com/user-attachments/assets/cb056b11-054c-4a06-a236-f4540b827c8b" />


# CAUTION

//ngl gang idek if this will still happen; but if it does its the same as before; i DID sign it this time just not paid version so idek

## I should've said this earlier, but when downloading you may get this error right here


![image](https://user-images.githubusercontent.com/34391969/211076893-afb76902-b636-4a71-80bb-b137c529534b.png)


## Just click more info and Run anyway;


![image](https://user-images.githubusercontent.com/34391969/211077062-cc46d087-3a62-454d-910d-6597e6d09129.png)


## The reason this shows up is besause im broke boi and can't pay to sign the package as a publisher right now

# Enjoy <3
