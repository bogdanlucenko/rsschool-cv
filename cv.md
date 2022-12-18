# Bohdan Lutsenko

## Web Developer

### Contacts:
- Phone number: +31-638-97-67-24 
- Discord: bohdanlutsenko#9192 
- [LinkedIn](https://www.linkedin.com/in/bohdan-lutsenko-b7b378258)

--- 

### About me:

My goal is to become a Front-End developer and work remotely. I devote almost all my free time to studying programming languages ​​and English. I believe in myself and in the fact that I can achieve what I want and no matter how long it takes me, the main thing is to work hard and make the appointed path.

---

### My skills so far:
- Strong knowledge of HTML and CSS
- Using the BEM methodology
- Using SCSS Preprocessors
- An adaptive layout of the site 
- Basic knowledge of JavaScript
- Basic knowledge of Git version control system

---

### Code example: 

#### Task:

*From the Google Autocomplete service, a response came with data in the form of an object:*

```
{
    formatted_address : "Washington Square, New York, NY 10012, Сполучені Штати Америки",
    geometry: {
        location: {
            lat: 40.7308838,
            lng: -73.997332
         },
         viewport: {
            northeast: {
               lat: 40.7333674,
               lng: -73.99379435000002
            },
            southwest: {
               lat: 40.72847220000001,
               lng: -74.00132615
            }
         }
      },
      name: "Washington Square Park"
}
```
> Write a script that will make a complete copy of the original object using recursion for nested objects.

> Output the original and the resulting result to the console.

### Solution:

```
let google = {
            formatted_address : "Washington Square, New York, NY 10012, Сполучені Штати Америки",
            geometry: {
                location: {
                    lat: 40.7308838,
                    lng: -73.997332
                 },
                 viewport: {
                    northeast: {
                       lat: 40.7333674,
                       lng: -73.99379435000002
                    },
                    southwest: {
                       lat: 40.72847220000001,
                       lng: -74.00132615
                    }
                 }
              },
              name: "Washington Square Park"
        }

        let newObj = clone(google);
        console.log('Original', google);
        console.log('Copy', newObj);
        
        function clone(copy) {
            let cloned = {};
            for (let key in copy) {
                if (copy[key] instanceof Object) {
                    cloned[key] = clone(copy[key])
                } else {
                    cloned[key] = copy[key];
                }
            }
            return cloned;
        }
```
---

### My projects:
- [CutSpace](https://bogdanlucenko.github.io/CutSpace) `--->`
  [Link to the repository](https://github.com/bogdanlucenko/CutSpace)
- [Tanatos](https://bogdanlucenko.github.io/Tanatos/) `--->` 
  [Link to the repository](https://github.com/bogdanlucenko/Tanatos)

  ---

### Completed courses:
- **Front-end Basic course** from [Hillel IT school](https://ithillel.ua/courses/front-end-basic)
- **Distance intensive elementary level course** from [Green Forest](https://greenforest.com.ua/)

### Knowledge of foreign languages:
- Pre-Intermediate English level
- Also constantly train live communication with native speakers
- Russian - Native
- Ukrainian - Upper-Intermediate