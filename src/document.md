

### 控制器 Controller

控制器主要来用控制路由，对进来的 url 进行处理。

```javascript
import { Controller, Get } from '@nestjs/common';

// 装饰器中使用路径前缀可以使我们轻松地对一组相关的路由进行分组，并最大程度地减少重复代码
@Controller('posts') 
export class PostsController {
  @Get()
  findAll(): string {
    return 'xxx';
  }
}
```









