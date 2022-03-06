Try to build the project with:

```
Run ./gradlew assembleDebug
```

_Output_:

```sh
* What went wrong:
Execution failed for task ':checkDebugDuplicateClasses'.
> A failure occurred while executing com.android.build.gradle.internal.tasks.CheckDuplicatesRunnable
   > Duplicate class a.a.a.a found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.a$a found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.b found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.c found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.d found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.e found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.f found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.k.a found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.l.a found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.l.b found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.m.a found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.m.a$a found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.m.b found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.m.c found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)
     Duplicate class a.a.a.m.d found in modules jetified-pos-comm-sdk-1.2.2-runtime (net.geidea.sdk:pos-comm-sdk:1.2.2) and jetified-stario10-1.0.0-runtime (com.starmicronics:stario10:1.0.0)

     Go to the documentation to learn how to <a href="d.android.com/r/tools/classpath-sync-errors">Fix dependency resolution errors</a>.
```
