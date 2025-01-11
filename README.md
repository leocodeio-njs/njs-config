#### Config Module

```bash
pnpm add @leocodeio-njs/njs-config
```

```typescript
// import helath module
import { AppConfigModule, AppConfigService } from '@leocodeio-njs/njs-config';

// Add the module to the imports array of your main module
@Module({
  imports: [AppConfigModule],
  controllers: [AppController],
  providers: [AppService, AppConfigService],
})
export class AppModule {}
```
