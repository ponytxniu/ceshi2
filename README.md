# JavaScript Snake Game

这是一个基于DOM的贪吃蛇游戏，是十多年前用JavaScript编写的，它被设计的有一种复古的风格。
## 在线玩游戏!

原版游戏在这里:

http://patorjk.com/games/snake


## 如何使用
 index.html 文件应该给出怎么使用此代码的用法，但是您可以在下面看到将其初始化到网页内的任何div中.
 
    var mySnakeBoard = new SNAKE.Board( {
                                            boardContainer: "game-area",
                                            fullScreen: false,
                                            width: 580,
                                            height:400
                                        });
                                    
源代码中的注释格式有点奇怪，因为我当时正在使用YUI Doc，它可以从代码生成文档。JavaScript世界里有如此多的混乱很多混乱的东西，这有点糟糕。但我很高兴其余的代码没有使用任何外部库，因为这个游戏在十多年后仍然可以正常工作。
