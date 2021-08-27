# Small description
1. File change_sever_name - expects 3 arguments on input, 1 arg - old name server name, 2 arg - new name server name, 3 arg - path to a directory containing 100 configuration file.
2. File timestamp - create 10 files named "test_t$T IMESTAMP_$NUM.txt" each one containing 1000 random characters.
3. File access_file_proccess - expect 1 argument on input, name processe. This script collect into "/tmp/investigation/" list of all the files accessed by processes which was passed in the argument. In the directory create files "filename = access_$PID.txt" wich contain list of accessed file per each process.
