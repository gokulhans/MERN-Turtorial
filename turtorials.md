# Read MD Tips

1. [x] Checked
2. [ ] Un Checked

Ctrl + Shift + V - For see preview of md file


# Router tips

router.get('^/$|/index(.html)?',(req,res)=>{
    res.sendFile(path.join(__dirname,'..','views','index.html'));
});

This works like if we type /index or /index.html or just \ , it loads the file index.html

# Middleware

- 3 types
- - Custom
- - Built IN
- - 3rd Party