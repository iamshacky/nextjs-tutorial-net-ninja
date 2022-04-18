# Next.js Tutorial #9 - Images & Metadata

Use the Image component in Next & also how to use the Head component to add titles and metadata to your pages.  

- Adding an image and making it the logo.

Author: Net Ninja  
https://youtu.be/rHncMH1CfCU?list=PL4cUxeGkcC9g9gP2onazU5-2M-AzA8eBw&t=36  

- Image component: Use image component instead of an img tag:  
import Image from 'next/image'  
and use image src instead of img src in image tag. (see navbar.js)  
https://youtu.be/rHncMH1CfCU?list=PL4cUxeGkcC9g9gP2onazU5-2M-AzA8eBw&t=74  

- Metadata  
Using the Head component built into next.js, import Head from 'next/Head'.  
<Head>  
<title>Ninja List | Home</title> (Names the chrome tab)   
meta name="keywords" content"ninjas"    
etc  
</Head>  

https://youtu.be/rHncMH1CfCU?list=PL4cUxeGkcC9g9gP2onazU5-2M-AzA8eBw&t=171  

Files used:  
- components/Navbar.js
- index.js
- about.js
