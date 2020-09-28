# patatapProject
Animation Sound Project

Patatap project is a fun application that works through two library

paperjs and howlerjs

Each key (letter) correspond to a sound

if you want to add different sound you have only to append value to your data array

var keyData = {

    theKeyYouWant: {
  
      sound: new Howl({
    
      src: ['yourFolder/YourSound.mp3']
    
      }),
    
      color: 'colorYouWant'
    
    }
