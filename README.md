### Sentinel, Mark 2, OSS Release

> there is a phone case for a pixel 10 that I recovered too in here, don't print it unless needed!

So, I have mentioned this before on my X profile, and that I have had a few considerations to keep in mind going forward - I even ran a poll. From this, the following points were reached to go forward:

- OpenSource the prototype body (this) - refactoring would result in breaking changes without the original CAD files (more on this momentarily), and at this point the hardware drift requires a complete redesign of the screen area.
- Use support from people seeing that this is an actual real thing, so I can actually build this properly.
- Promoting my ethic of 'federated' industrial design.
- The hardware that would go in this is *incompatible* with my current firmware standard, and is far too limiting - costs of compromise are overtaking any form of gain from using less powerful hardware.
- As of today (April 26th, 2026) I have had multiple components necessary for the board setup either run out of stock, or otherwise increase to a point of diminishing returns in cost.
- IP65 verifying all of this on top is going to cost thousands, so just releasing this current model and stating 'Use at own risk' is the only way forward in my eyes that doesn't have me forking out funding I do not have to potentially have to completely redesign it anyway 

So, with that in mind, that is what this is.

Now I mentioned the CAD files! These got lost in an 'incident' involving data loss - but the 3MF files were on my printer, so could be taken off and that is what the files here are!

### Caveats
- Obvious first: there is no hardware (electronic) present in this release. You are going to need to supply your own.
- Currently there is no I/O plate, for some reason this file never got stored, it wasn't finished anyway.
- It is very cramped inside as the chassis build pre-dates the modular board designs, and was actively in development when the 'whoopsie' happened.
- I cannot currently provide you a good reccomendation for a display, but I used a 2.8" Display (claims it is a ST7789, who knows what it actually is but it is not that), these issues are partly responsible for the refactor going ahead regardless of data loss.
- I also cannot openly reccommend you a reliable power supply, there are 4 holes in the chassis base that were to be used for a modular solution - this board design got lost but this should be fairly easy to work with.
- There are no threads, you will *NEED* to use brass inserts unless you want to redo it.
- drift, this was a prototype and non-final, it awaiting a complete rebuild after figuring out sizing.

### Things that do work
- Keypads for this are widely available & it is basically down to choice how much you choose to pay for the solution - they are 50/52mm x 70mm, and are stocked by most suppliers, there will be an image below of this if viewing via GitHub web.

![This exact model, no part number](https://arduwiki.com/html/images/thumb/a/a9/3X4%ED%82%A4%ED%8C%A8%EB%93%9C%EB%8C%80%ED%91%9C%EC%9D%B4%EB%AF%B8%EC%A7%80.jpg/800px-3X4%ED%82%A4%ED%8C%A8%EB%93%9C%EB%8C%80%ED%91%9C%EC%9D%B4%EB%AF%B8%EC%A7%80.jpg?20240104083140)
(I could never find the part number, another reason for refactor is escaping relying on 'maker components')

### Usage
Print it. I never got around to testing different forms of plastic, but I did try PLA in multiple colours and had no issues. I cannot 100%

All screws are assumed to be M2, and you will need brass inserts for the posts.

The handle/frame needs to be inverted prior to printing for the 'other half' - doing this in FreeCAD yielded disaster for some reason when slicing

I used Bambu Studio

### Notes
At production, obviously my documentation and release would be far more polished than this, but as you can gather from the reasons behind why I did this that ideally I wanted the release to be at pre-orders, not via a GitHub repository.

This is not representative of the final state, nor of any cancellation/termination of my intent to actually produce the Sentinel.

Thank you!

> Savannah @ Federated Industrial

### Licence

AGPL, do not assume this to reflect the final product and is a DISTINCT and SEPARATE thing.
