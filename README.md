---
invoice: 34843
date   : 2001-01-23
bill-to: &id001
    given  : Chris
    family : Dumars
    address:
        lines: |
            458 Walkman Dr.
            Suite #292
        city    : Royal Oak
        state   : MI
        postal  : 48046
ship-to: *id001
product:
    - sku         : BL394D
      quantity    : 4
      description : Basketball
      price       : 450.00
    - sku         : BL4438H
      quantity    : 1
      description : Super Hoop
      price       : 2392.00
tax  : 251.42
total: 4443.52
comments: >
    Late afternoon is best.
    Backup contact is Nancy
    Billsmer @ 338-4338.

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
