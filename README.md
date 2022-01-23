# C-Sharp-proscripts


### Change program name after running it.
```CSHARP
//KEYAUTH.WIN BEST AUTHENTICATION SERVICE FOR YOUR PROGRAM.
//KEYAUTH.WIN BEST AUTHENTICATION SERVICE FOR YOUR PROGRAM.
using System;

namespace ConsoleApp69
{
    class Program
    {

        static void Main(string[] args) 
        {
             AppDomain.CurrentDomain.ProcessExit += new EventHandler(lolxd_ProcessExit);
        }

        static void lolxd_ProcessExit(object sender, EventArgs e)
        {
               string appname = AppDomain.CurrentDomain.FriendlyName;
               string randomname = randomi(10);
               Process.Start(new ProcessStartInfo("cmd.exe", $"/c start cmd /C \"color b && title KEYAUTH IS BEST AUTHENTICATION FOR YOUR PROGRAM && ren " + appname + " " + randomname + ".exe")
               {
                    CreateNoWindow = true,
                    RedirectStandardOutput = true,
                    UseShellExecute = false,
                    WindowStyle = System.Diagnostics.ProcessWindowStyle.Hidden
               });
               Environment.Exit(0);
        }

        private static string randomi(int length)
        {
            string letters = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUXYZ0123456789";
            Random random = new Random((int)DateTime.Now.Ticks);

            string randomString = "";
            for (int i = 0; i < length; i++)
            {
                randomString += letters[random.Next(0, letters.Length - 1)];
            }

            return randomString;
        }
    } 
}

//KEYAUTH.WIN BEST AUTHENTICATION SERVICE FOR YOUR PROGRAM.
//KEYAUTH.WIN BEST AUTHENTICATION SERVICE FOR YOUR PROGRAM.
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```


### SOON
```
Soon
```

### SOON
```
Soon
```


### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```

### SOON
```
Soon
```
