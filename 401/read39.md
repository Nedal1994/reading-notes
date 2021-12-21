# Read39 Summary

![mobx](https://mobx.js.org/assets/getting-started-assets/overview.png)

MobX is a simple, scalable and battle tested state management solution. This tutorial will teach you all the important concepts of MobX in ten minutes. MobX is a standalone library, but most people are using it with React and this tutorial focuses on that combination. State is the heart of each application and there is no quicker way to create buggy, unmanageable applications than by producing an inconsistent state or state that is out-of-sync with local variables that linger around. Hence many state management solutions try to restrict the ways in which you can modify state, for example by making state immutable. But this introduces new problems; data needs to be normalized, referential integrity can no longer be guaranteed and it becomes next to impossible to use powerful concepts like classes in case you fancy those. MobX makes state management simple again by addressing the root issue: it makes it impossible to produce an inconsistent state. The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived. Automatically.

![hookstate](https://miro.medium.com/max/1024/1*3LMhVyKAWHOBmUtFrURNbw.png)

Hookstate is a modern alternative to Redux, Mobx, Recoil, etc. It is simple to learn, easy to use, extendable, very flexible and capable to address all state management needs of large scalable applications. It has got impressive performance and predictable behavior.