# LJ Code 201 - Day 17

Today my group spent most of the time coding together as a trio. We initially coded this way so that Smitty and I could get some more practice with adding persistence to our pages. But as the day went on, we went back to coding together so that we could each get a chance at writing the scripts. I did pick up a tip or two from coding with my team. When putting together one of our functions, we pseudo-coded what we wanted to do and what we would need to create as we went along. This helped us know what else we would need to create to get what we wanted.

Here's the snippet we worked on in which we put to use this practice of active pseudo-coding:

    function main() {
        //match selectionCriteria.region to the subset of trails in the correct region
      var regionalTrails = selectRegion();
        //select best match
      var bestTrail = selectTrail(regionalTrails);
        //render best trail
      renderTrail(bestTrail);
    }
