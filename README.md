---
title: Our Cool Project
services: virtual-machines, documentdb
---

Azure Friday
=======

Trusted voices at the center of the Enterprise and Cloud computing.

I learn best when a trusted friend sits down with me and we pair on a problem. Just two engineers, a laptop and the cloud, solving problems. I'm trying to bring that experience to you every Friday. No editing, no marketing, just solutions. -- Scott Hanselman.

    using System.Web;
    using System.Web.Mvc; 
    
    namespace MvcMovie.Controllers 
    { 
        public class HelloWorldController : Controller 
        { 
            // 
            <mark>// GET: /HelloWorld/ </mark>
    
            public string Index() 
            { 
                return "This is my <b>default</b> action..."; 
            } 
    
            // 
            // GET: /HelloWorld/Welcome/ 
    
            public string Welcome() 
            { 
                return "This is the Welcome action method..."; 
            } 
        } 
    }
