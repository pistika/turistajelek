<p align="center">
<br><br>
<a target="_blank" href="https://github.com/pistika/turistajelek"><img src="assets/img/logo.png" alt="Logo" width="250" /></a>
</p>

<h2 align="center" align="center">Túristajelek, Hungarian Trail Signs</h2>
<p align="center">Add trail signs to your html content. These are small inline SVG-s that are added to your content with a single CSS file.<br><br>Just add a few classes and have all the signs in all the colors that you'd ever need.<br><br><a href="https://pistika.github.io/turistajelek/" target="_blank">Check it out here!</a></p>

<!-- GETTING STARTED -->
### Usage

```
1. Download the *-latest.css or *-latest.min.css file from GitHub
2. Link it in your <head>
3. Use the classes below
4. Profit
```
  
<p>A single CSS file that contains the SVG text content and uses the :before pseudo selector and the content property to insert these SVGs. No further requests to file anywhere.<br>
All SVGs are white and have negative space / cutout in them, making some parts transparent. These holes reveal the background color underneath, so any color can be used to insert these signs, no need to have multiple versions of the same sign just to have different colors.</p>
  
  
### Example

This is a basic example, it will insert a blue line/stripe sign where it is.

`<i class="jel jel-line jel-color-blue"></i>` -> <img src="assets/svg/vonal_bg.svg" height="16" />

```
The basic code must contain 3 class names:
- jel
    This is always required

- jel-color-{COLOR} or jel-szin-{COLOR}
    Ready to use color names:
        blue / kék / kek - rgb(0, 59, 128)
        red / piros - rgb(199, 23, 18)
        yellow / sarga / sárga - rgb(252, 184, 33)
        green / zold / zöld - rgb(36, 145, 64)
        purple / lila - rgb(125, 31, 122)
        black / fekete - rgb(0, 0, 0)
        grey / gray / szurke / szürke - rgb(128, 128, 128)

- jel-{SIGNNAME}
    All signs and names are listed at the end of the page
```
    
    
#### Signs   

| Icon | Name | Class(es) |
|------|------|-----------|
|<img src="assets/svg/barlang_bg.svg" height="32" />|Barlang / Cave|`.jel-barlang .jel-cave`|
|<img src="assets/svg/bicikli_bg.svg" height="32" />|Kerékpár / Bike|`.jel-bicikli .jel-bike`|
|<img src="assets/svg/csucs_bg.svg" height="32" />|Csúcs / Summit|`.jel-csucs .jel-csúcs .jel-haromszog .jel-háromszög .jel-top .jel-triangle`|
|<img src="assets/svg/emlekmu_bg.svg" height="32" />|Emlékmű / Memorial|`.jel-emlek .jel-emlék  .jel-emlekmu .jel-emlékmű .jel-memorial .jel-monument`|
|<img src="assets/svg/forras_bg.svg" height="32" />|Forrás / Source|`.jel-forras .jel-forrás .jel-source`|
|<img src="assets/svg/gyongy_bg.svg" height="32" />|Gyöngy / Pearl|`.jel-gyongy .jel-gyöngy .jel-pearl`|
|<img src="assets/svg/jakab_bg.svg" height="32" />|Jakab / Santiago|`.jel-jakab .jel-santiago .jel-pearl`|
|<img src="assets/svg/kapolna_bg.svg" height="32" />|Kápolna / Chapel|`.jel-kapolna .jel-kápolna .jel-templom .jel-chapel .jel-temple`|
|<img src="assets/svg/kereszt_bg.svg" height="32" />|Kereszt / Cross|`.jel-kereszt .jel-cross`|
|<img src="assets/svg/kor_bg.svg" height="32" />|Kör / Circle|`.jel-kor .jel-kör .jel-pont .jel-circle .jel-round .jel-dot`|
|<img src="assets/svg/maria_bg.svg" height="32" />|Mária / Maria|`.jel-maria .jel-mária`|
|<img src="assets/svg/mz_bg.svg" height="32" />|Magyar Zarándokút / Hungarian Pilgrimage|`.jel-mz .jel-magyarzarandok .jel-hungarianpilgrim .jel-hp .jel-mzarandok .jel-hpilgrim`|
|<img src="assets/svg/pecset_bg.svg" height="32" />|Pecsét / Stamp|`.jel-pecset .jel-pecsét .jel-kód .jel-kod .jel-stamp .jel-code`|
|<img src="assets/svg/rom_bg.svg" height="32" />|Rom / Ruin|`.jel-rom .jel-ruin`|
|<img src="assets/svg/situra_bg.svg" height="32" />|Sítúra / Skitour|`.jel-situra .jel-sítúra .jel-ski .jel-skitour`|
|<img src="assets/svg/tan_bg.svg" height="32" />|Tanösvény / Education|`.jel-tan .jel-tanosveny .jel-tanösvény .jel-edu .jel-education`|
|<img src="assets/svg/telep_bg.svg" height="32" />|Település / Settlement|`.jel-telep .jel-telepules .jel-település .jel-settlement .jel-education`|
|<img src="assets/svg/veszely_bg.svg" height="32" />|Veszély / Danger|`.jel-veszely .jel-veszély .jel-vigyazz .jel-vigyázz .jel-danger .jel-warning`|
|<img src="assets/svg/vonal_bg.svg" height="32" />|Sáv / Line|`.jel-sav .jel-sáv .jel-vonal .jel-csik .jel-csík .jel-line .jel-band .jel-stripe`|
|<img src="assets/svg/unknown_bg.svg" height="32" />|Alapértelmezett, ismeretlen / Default, unknown| - |
  
  
#### Colors

| Color | Name | Class(es) |
|------|------|-----------|
|<img src="assets/img/blue.png" height="32" />|Kék / Blue|`.jel-kek .jel-kék .jel-blue`|
|<img src="assets/img/red.png" height="32" />|Piros / Red|`.jel-piros .jel-red`|
|<img src="assets/img/yellow.png" height="32" />|Sárga / Yellow|`.jel-sarga .jel-sárga .jel-yellow`|
|<img src="assets/img/green.png" height="32" />|Zöld / Green|`.jel-zold .jel-zöld .jel-green`|
|<img src="assets/img/purple.png" height="32" />|Lila / Purple|`.jel-lila .jel-purple`|
|<img src="assets/img/black.png" height="32" />|Fekete / Black|`.jel-fekete .jel-black`|
|<img src="assets/img/gray.png" height="32" />|Szürke / Gray|`.jel-szurke .jel-szürke .jel-gray .jel-grey`|    
    

#### Modifiers
```
- jel-nincsarnyek / jel-noshadow (class)
This will remove the CSS dropshadow from the sign

- jel-keret / jel-border (class)
This will add a smell color matching border to the sign

- jel-nincsterkoz / jel-nowhitespace (class)
Removes the spacing before and after the sign

- jel-kicsi / jel-sm / jel-small (class)
Smaller version. This will make the height 0.75em tall.

- jel-nagy / jel-big / jel-lg / jel-large (class)
Bigger version. This will make it 1.5em tall.

- any background CSS style property (attribute)
    style="background-color: teal;"
    style="background-color: rgba(12, 99, 200, 0.89);"
    style="background-image: linear-gradient(red, yellow);"
    Any valid CSS property value pair should work
```


<p align="center">
<img src="assets/img/screenshot.png" alt="Screenshot" />
</p>

### Customizing

1. Download the -latest.scss
2. Modify to your needs
3. Build / compile
4. Profit

### Todos

- I know there are some missing signs, mostly region and event specific ones. I'll try to trace and update all of them as quickly as I'm able to.
    
    
## Contributing
I don't know how much will I maintain this thing, but if you think you have something to contribute:

1. Fork the Project
2. Create your Feature Branch (`git checkout -b changes/modifysomethingpls`)
3. Commit your Changes (`git commit -m 'Add some modifysomethingpls'`)
4. Push to the Branch (`git push origin changes/modifysomethingpls`)
5. Open a Pull Request
    
    
## License
pistika/turistajelek is licensed under the GNU Affero General Public License v3.0. See `LICENSE` for more information.