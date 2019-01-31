# TUIO TouchToy

## About

- This is a Altered Qualia's [TouchToy Experiment](http://alteredqualia.com/touchtoy/) adapted for [TUIO](https://www.tuio.org/).
- It receives TUIO 2.0 via Websocket on port 8080 using [tuio-extended](https://github.com/nomve/Tuio.js).
- You can use it on Macbook trackpads with [Tongseng](https://github.com/fajran/tongseng).

## Development

- I have modified the script to merge TUIO signals into a list of active touch ids 
- In the past you might have used [Magic Touch](https://github.com/borismus/MagicTouch) with [npTuioClient](https://github.com/fajran/npTuioClient), but this approach does not work anymore since NPAPI plugins are not supported anymore.


## Usage

- Touch the screen to create particles at your fingertips.  
- Lift all fingers to clear the screen.  
- Double tap to open menu for selecting different particle themes.

## License

GPL licensed

