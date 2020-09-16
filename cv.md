# Turebekov Arman
> Frontent Developer

## Contacts
* Phone number: + 7707 350 03 43
* Email: turebekov.arman@gmail.com

## About Me
*I graduated from the Polytechnic College and entered the Polytechnic 
University but did not graduate I thought that I could learn and get a 
job myself befor I've had a great enthusiasm for technology since an early age.*

*I took online courses approved by my brothers and learned  how to code.
 My brothers are developers*

*My strengths are persistence and courage. I give my all to acgieve my goals in spite of any
 hardships I might encounter along the way. I have a hard-working nature. 
 I am always looking for ways to improve and grow *
 
 
## Skills

**JavaScript   HTML CSS jQuery Vue.js Angular Bootstrap Git OpenLayers MVC Knockout.js
Ajax Laravel PHP**

## Code examples
```javascript

 getOrderTextDifference(orderText) {
     if (!this.orderTextReserve) {
       return orderText;
     } else {
       const re = /<[^>]*>|(&nbsp;)/gi;
       const orderTextArr = orderText.replace(re, ' ').split(' ').filter(str => str !== '');
       const orderTextReserveArr = this.orderTextReserve.replace(re, ' ').split(' ').filter(str => str !== '');
       const newWords = orderTextArr.filter(str => {
         if (!orderTextReserveArr.includes(str)) {
           return str;
         } else {
           const strIndex = orderTextReserveArr.indexOf(str);
           orderTextReserveArr.splice(strIndex, 1);
         }
       });
       if (newWords.length > 0) {
         return newWords.join('; ');
       }
     }
   }
   
   function balancedString(str) {
       if (1 <= str.length <= 1000) {
           let countR = 0, countL = 0;
           let balanceStr = 0;
           for (let i = 0; i < str.length; i++) {
               if (str[i] === 'R') {
                   countR++;
               }
               if (str[i] === 'L') {
                   countL++;
               }
               if (countR === countL) {
                   balanceStr++;
               }
           }
           return balanceStr;
       }
   
   }
   
   //console.log(balancedString('RLLLLRRRLR'));
   
   
//console.log(intersectionTwoArrays([8, 0, 3], [0, 0]));

function intersectionTwoArrays(nums1, nums2) {
    if (nums1.length > nums2.length) {
        return renderAndFindNumbers(nums1, nums2);
    } else {
        return renderAndFindNumbers(nums2, nums1);
    }
}

function getUniqueValues(values) {
    return [...new Set(values)];
}

function renderAndFindNumbers(nums1, nums2) {
    let result = [];
    nums2 = getUniqueValues(nums2);
    for (let i = 0; i < nums2.length; i++) {
        let found = nums1.find(num => num === nums2[i]);
        if (found || found === 0) {
            result.push(found);
        }
    }
    return result;
}
   ```

## Work experience 
> 2 years 11 months

**ТОО KAZGISA**

`Frontend developer
 Completing complex weekly tasks, I began to Google correctly and found 
 perseverance in myself.
 With the support of the geo-portal, I learned to debug and write readable code. 
 Made a dynamic layer panel and reduced the code by 1000 lines. When refactoring
  code, steel is mindful of the little things, gave meaningful names, and applied
   a recursive function. Participated in the development and support of projects
    in Vue.js, Angular, Knockout.js. Developed modules for existing projects and 
    participated in the development of geographic information portals and 
    e-service portals.
 I learned to interact with a designer and a project team. Design solutions
  together with backend developers. Steel better understand the development
   process, work in a team and work with GIT.`



