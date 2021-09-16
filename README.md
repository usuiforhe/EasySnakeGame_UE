<!--
 * @Author: your name
 * @Date: 2021-09-16 10:37:19
 * @LastEditTime: 2021-09-16 10:41:43
 * @LastEditors: Please set LastEditors
 * @Description: In User Settings Edit
 * @FilePath: \undefinedd:\Projects\unreal\EasySnakeGame_UE\README.md
-->
# EasySnakeGame_UE
 虚幻制作简单贪吃蛇

由BP_SnakeBody作为身体、BP_SnakeHead作为头、BP_Food作为食物  
Head保存下一级Body的引用，Body保存着它下一个Body的引用，依次调用  
BP_Food使用球形射线检测，判断生成的位置是否有蛇的身体或头或其他食物，确保食物生成在一个没有触碰的坐标  