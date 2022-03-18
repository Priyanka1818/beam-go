# beam-go
## . First Download Go. [Go download](https://go.dev/dl/)

## . Install Go.

## . Create a folder named 'beam-go'

## . Open gitbash and type this command

go mod init github.com/<Priyanka1818>/beam-go

## . For version of go, use this command:

go version

## . For getting Apache beam SDK,

go get -u github.com/apache/beam/sdks/v2/go/pkg/beam

## . For wordcount program,

go install github.com/apache/beam/sdks/v2/go/examples/wordcount

##  . To run the wordcount program, type in the command

wordcount --input sample.txt --output count

## . The output file will be generated with the name "counts".
