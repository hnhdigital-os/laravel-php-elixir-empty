```
__________.__          ___________.__  .__       .__        
\______   \  |__ ______\_   _____/|  | |__|__  __|__|______ 
 |     ___/  |  \\____ \|    __)_ |  | |  \  \/  /  \_  __ \
 |    |   |   Y  \  |_> >        \|  |_|  |>    <|  ||  | \/
 |____|   |___|  /   __/_______  /|____/__/__/\_ \__||__|   
               \/|__|          \/               \/          
                                                Empty Module
```

Provides the ability to completely remove files in a specified folder.

### Empty

Deletes all files and folders in the listed paths.

```yaml
empty:
    - PATH_PUBLIC_ASSETS
    - PATH_PUBLIC_BUILD
```

This module automatically stpos clearing of files/folders that are within the the public path. You can force delete by prepending `?force=1`.