# "Framer Motion animate on state update" test on version 9.0.0

Replicate the [Example](https://codesandbox.io/s/framer-motion-animate-on-state-update-ns67ib?from-embed=&file=/package.json:165-189) from Framer Motion documentation.

In Framer Motion from version 9.0.0, when changing the value suddenly, the .box div move/ rotate smoothly. Try it in my [Replication](https://framer-motion-test-9-0-0.vercel.app/) that I have deployed with Framer Motion version 9.0.0.

However, in Framer Motion version 10.0.0 and older, the .box div responds slower than expected and only move/ rotate properly when I stop changing the value or click to change the value. Try it in my [Replication](https://framer-motion-test-10-0-0.vercel.app/) that I have deployed with Framer Motion version 10.0.0.
