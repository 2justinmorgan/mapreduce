# MapReduce

contributors: Alexa White and Justin Morgan

to build plugin(s):

    go build mr/mr.go

    go build -buildmode=plugin <*.go>...

to compile:

    go build main.go worker.go fmanager.go

to run:

    ./main <input_file.txt> <*.so>
	
       or

	 (will build plugins, compile, and run code)
    ./run.sh <input_file.txt>

to test:

    go test

       or

    go test -v

       or

    go test -run <TestFunctionName>

