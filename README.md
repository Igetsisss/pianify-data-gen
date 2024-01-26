# Song Data Generator

Welcome to the Song Data Generator, a web app designed to help you easily create and manage data for your favorite songs. Made for Pianify but can be used for any purpose by fork.

## Get Started

To generate data for a song, follow these simple steps:

1. Fill in the required information in the form.
   - **Index**: Enter the song index.
   - **Song Name**: Provide the name of the song.
   - **Song Image URL**: Insert the URL for the song image.
   - **Song Artist**: Specify the artist of the song.
   - **Track Time**: Enter the duration of the song.

2. Click the "Generate Data" button.

3. The generated data will be displayed below, and you can copy it to use as needed.

## Generated Data

The generated data will be in the following format:

```json
{
    "index": "1",
    "songName": "Dark Beast Ganon Theme",
    "songimg": "https://i.scdn.co/image/ab67616d0000b27314f448ae9efd01a34344c075",
    "songArtist": "Manaka Kataoka",
    "link": "https://audio.jukehost.co.uk/y554YOfzTrB6ZlMCZw4984HyYUEyrAil.mp3",
    "trackTime": "4:07"
}
```

##Multiple Songs
You can generate data for multiple songs sequentially, and the app will keep track of each song's data. Each set of song data will be displayed with a "Copy" button for easy copying.

##Run the App Locally
If you want to run the app locally, download the provided HTML file and open it in a web browser. The app will guide you through the process of generating song data.

Feel free to use this Song Data Generator to organize and manage your favorite music collection!
