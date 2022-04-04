# Cobra installation
go get -u github.com/spf13/cobra

# Create cli project
```
mkdir mycli
cd mycli
cobra init --pkg-name mycli
go mod int mycli
go mod tidy 
```

# Add command
cobra add hello

# Build
go install or go build


