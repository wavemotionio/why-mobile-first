# Why “Mobile-First”?

1. Common Misconceptions
1. Pros: So, then why “mobile-first”?
1. Cons: What must we watch out for?

***

## Common Misconceptions

#### FALSE: Mobile-first means that the target audience includes smart phones or tablets.
Mobile-first is a methodology that increases the intrinsic value of the web application regardless of the target audience’s device. Window re-sizing and zooming must be considered for web applications running on a desktop experience.

#### FALSE: Mobile-first is pointless because we will author a native OS application, or outsource the creation of one, if we need to support mobile devices.
There are more options to consider when switching from a web application to a native application, such as whether the user requirements involve native OS features, application availability (must it be downloaded from the iphone or android store), and more. Shy of these additional requirements, a web application will suffice. If a native OS application is needed, mobile-first user workflows and UI views are already paid for and only a technology conversion is required. A responsible mobile-first approach will cost us less to support a mobile device in the future but will ensure pay off regardless.

#### FALSE: Mobile-first means that the application will be ready for tablets.
When assessing device-compatibility there is more to consider aside from mobile-first design principles. For instance, touch screen interactions and browser compatibility (not all devices support all browsers).

#### FALSE: Mobile-first is over-engineering of a web application.
Mobile-first design principles provide web applications intrinsic value regardless of the target device. It is about engineering for agility -- being prepared structurally so that product teams can deliver business features free of the burden of having to contemplate design concepts at the Product Backlog Item level.

***

## Pros: So, then why “mobile-first”?

> Mobile-first design principles enable agility.

In terms of iterative design, a mobile-first approach adds bells and whistles as the screen scales up. This way we do not lose elements of the user’s critical journey as we scale the screen size down. The goal is to develop software that is focused, simple to scale, and does not require infrastructure planning feature by feature so that:

1. __Designers will focus on critical user journeys__
    By starting in a small window, we guarantee that the most important features are accessible to the user by the mere fact they are using a web browser.
1. __Developers will focus on delivering business features__
    In most cases, developers are already using debugging tools and IDEs that reduce browser window side. Unresponsiveness becomes extremely obvious, must be actively ignored and accomodated during a typical workflow.
1. __QA can focus on features involved in critical user journeys__
    Focused views make the software more simplistic and predictable.

Additionally, this forces us to think about focused screens which has even more invaluable benefits right out of the box:

4. __Performance gains due to less assets to load and render.__
    Less on the screen = less elements to render = faster load times.
1. __Maintenance efficiencies due to decreased complexity.__
    The simplicity of focused, faster-loading views are easier for everyone (owners and newcomers) to document and understand. 
1. __Less technical debt to pay off on accessibility later.__
    Planning is not required to accomodate zooming, window resizing, and alternative screen-sized devices.
1. __More simplistic state management.__
    __Deterministic URLs -__ State retention is more predicable and in-bound integrations become free from the UI perspective.
    __Native browser features -__ Bookmarks, forward and back arrows, and the refresh button will work reliably.
    __Easier to test -__ Less bugs into production.

***

## Cons: What must we watch out for?

1. Testing at variable screen-sizes must become a part of the team's culture.
1. Legacy software is not applicable. It will be easier to adopt this methodology in new projects.
1. It requires that we think very differently about how we design the software.
1. Restricted workflows

***

# What else?

Please provide feedback.

