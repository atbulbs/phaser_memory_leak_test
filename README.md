# phaser memory leak test demo

# to phaser author
  We built a SPA and use phaser to create game. In our project, the game instance created and destroyed for many times. Mean while, we found that, the momory
  increased every time.What was the worest, our app in mobile always crashed, so we test the memory leak by this demo. Looking forward to your reply.

# run test
 * open the link [https://atbulbs.github.io/phaser_memory_leak_test/](https://atbulbs.github.io/phaser_memory_leak_test/)
 * input the times create and destroy phaser game, it's dedault value is 10
   ![1](/images/1.png)
 * open the chrome dev tool and change to Memory tab, then take a Heap snapshot
   ![2](/images/2.png)
   ![3](/images/3.png)
 * click run test button
   ![4](/images/4.png)
 * when the test is ended, take a Heap snapshot again
   ![5](/images/5.png)
   ![6](/images/6.png)
   ![7](/images/7.png)
 * then you can check the memory difference
   ![8](/images/8.png)
 * and you can filter some classes
   ![9](/images/9.png)
   ![10](/images/10.png)