# Vladislav Susikov

## Contact info

- City: Samara
- Email: susikovvlad2gmail.com
- GitHub: [Enyng](https://github.com/EnyngS)
- Codewars: [EnyngS](https://www.codewars.com/users/EnyngS)

## About me

I am a final year student. I have been studying web development for about 1 year. Participated in hackathons, developed small websites.

## Education

- [Coursera, JavaScript](https://coursera.org/share/6f495e2de44869153543fff88480b382)
- Selfeducation [JavaScript.ru](https://learn.javascript.ru/),[YouTube](https://www.youtube.com/c/FreelancerLifeStyle)
- SSAU, bachelor(2022)

## Skills

- Html,Css
- JavaScript
- Git
- Gulp
- React(Begginer)
- Decentraland ECS Utils
- English - A2

## Projects

- [MoGo](https://enyngs.github.io/site/)
- [React](https://enyngs.github.io/game/)
- [School Voice](https://enyngs.github.io/voice/)
- [Landing](https://enyngs.github.io/Run/)

## Code example

```
let decodeMorse = function(morseCode){
	let a = morseCode.split('   ');

	let res= a.map((b)=>b.split(' '))

  	let result = res.map((b)=>{
   	let val =[];
   	for(let value of b){
   	if(value) {
			val+=MORSE_CODE[value.trim()]
			}
    }

    return val
  });

  return result.join(' ').trim();
}
```
