###`goog.math.Vec2`API
* `goog.math.Vec2(x,y)` 创建一个二维向量对象,并返回
* `goog.math.Vec2.randomUnit()`创建一个随机的二维单位向量对象
* `goog.math.Vec2.fromCoordinate()`根据一个坐标点创建一个二维向量对象
* `goog.math.Vec2.prototype.clone()`克隆返回一个新的二维向量对象
* `goog.math.Vec2.prototype.magnitude()`返回当前向量模
* `goog.math.Vec2.prototype.squaredMagnitude()`返回向量模平方
* `goog.math.Vec2.prototype.invert() `反转向量方向
* `goog.math.Vec2.prototype.normalize()`返回当前向量的单位向量
* `goog.math.Vec2.prototype.add (b)`当前向量与b向量相加
* `goog.math.Vec2.prototype.subtract(b)`当前向量减去b向量
* `goog.math.Vec2.prototype.rotate(angle)`顺时针旋转angle角度,并返回新向量
* `goog.math.Vec2.rotateAroundPoint(v,axisPoint,angle)`把向量v相对于坐标点axisPoint旋转angle度
* `goog.math.Vec2.prototype.equals(b)`当前向量与b向量是否相同
* `goog.math.Vec2.distance(a,b)` a=>b之间距离
* `goog.math.Vec2.squaredDistance(a,b)`a=>之间距离平方
* `goog.math.Vec2.equals(a,b)`向量a与向量b是否相同
* `goog.math.Vec2.sum(a,b)`两个向量相加
* `goog.math.Vec2.difference(a,b)`向量a减去向量b
* `goog.math.Vec2.dot(a,b)`两个向量点乘
* `goog.math.Vec2.lerp (a,b,x)`a,b向量中间x分割点
