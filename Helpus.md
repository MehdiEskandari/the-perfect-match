npx create-react-app catpure

---

src > make a folder (img: copy and peast images)

clean up some file here...
Delete: index.css, App.css, App.test.js, logo, setupTests.js

---

npm install react-router-dom framer-motion react-intersection-observer styled-components

---

src > make a folder (components > AboutSection.js)

## Put basic jsx things into the AboutSection.js

import React from 'react';

    const AboutSection = () => {
        return (

        )
    }

    export default AboutSection;

Before use any images you must import it.

src > make a folder (pages > AboutUs.js).
We make a few components in components folder
then insert them into the whole AboutUs page.

Eventually, we insert pages into the App.js

whats meaning of chuks?


----

src > make a file (components > ServicesSection.js)
We make a few components in components folder
then insert them into the whole AboutUs page.


---
styled components
put the style next to the export line
like this:
container = <use-styled-component>.<element>` write your css here`
const About = styled.div`
  min-height: 90vh;
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 5rem 10rem;
  color: white;
`;

but maybe we need to add global css
src > make a new file (components > GlobalStyle.js)
and inside of that you need to import someting

after write some line of css code in AboutSection (Styled Comopnents)

we make a new file in src folder and make a new file styles.js
then moved reusable Styled Comopnents into the this file and don't forget import styled from 'styled-components'

Then export each of them 
for example:
  export const Hide = styled.div`
    overflow: hidden;
  `;

Then you can simply import them like this:
import { About, Description, Hide, Image } from '../styles';

for styling Services we can copy all css in About or we can 
write this :

const Services = styled(About)`
  ...css here
`;

both of them do the same things

After styling we need to add font
google fonts > inter & lobster > embeded > peast into the index.html