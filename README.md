# 66_3360
常用优化方法-对象池GameObjectPool
<br/></br>
<h3>微:mukewang8 资源编号：523360</h3>
<br/></br>
<h3>课程介绍：</h3>
<p>在游戏开发中，使用对象池<a title="查看与 GameObjectPool 相关的文章" target="_blank">GameObjectPool</a>缓存频繁使用的对象。是很重要的优化方法。</p>
<p>在游戏场景中，我们有时候会需要复用一些游戏物体，比如常见的子弹、子弹碰撞类，某些情况下，怪物也可以使用池管理，UI部分比如：血条、文字等等。</p>
<p>这些元素共同的特性是：存在固定生命周期，使用比较频繁，场景中大量使用。</p>
<p>所以，我们就通过池管理思路，在游戏初始化的时候，生成一个初始的池，存放我们要复用的元素。</p>
<p>当要用到时，从池中取出；生命周期结束，放回到池中。</p>
<p><img src="https://www.ko996.com/wp-content/uploads/img/2018/08/2-29-300x145.png" alt="常用优化方法-对象池GameObjectPool"></p>
<h3>课程截图：</h3>
<p><img src="https://www.ko996.com/wp-content/uploads/img/2018/08/3-25.png" alt="常用优化方法-对象池GameObjectPool"></p>
