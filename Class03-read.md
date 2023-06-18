# Class 03 Reading notes 

- ## I/O stream

    - File and directory operations in the `System.IO` namespace enable creating, copying, and deleting files, as well as manipulating directories.
    - `Streams`, represented by the Stream class, allow reading from and writing to different storage mediums such as disks, memory, networks.
    - Reader and writer classes handle character encoding when reading from and writing to streams.
    - Asynchronous I/O operations should be used for resource-intensive tasks to maintain application responsiveness.
    - The System.IO.Compression namespace provides classes for compressing and decompressing files and streams.
    - Isolated storage offers a secure virtual file system for storing application data.
    - Security considerations, such as access control lists, should be followed when performing I/O operations.
    - When working with I/O operations, it is important to consider security policies and use isolated storage when appropriate.



- ## Write To a file

    - regarding to my knowledge the read and write is Console.Write ( Console.WRiteLine) and Console.Read, Console.ReadLine the difference between line and without line is line break the pointer get down 1 line.
    - StreamWriter contains methods to write to a file synchronously (Write and WriteLine) or asynchronously (WriteAsync and WriteLineAsync).

    - File provides static methods to write text to a file such as WriteAllLines and WriteAllText, or to append text to a file such as AppendAllLines, AppendAllText, and AppendText.
    - Path is for strings that have file or directory path information. It contains the Combine method and in .NET Core 2.1 and later, the Join and TryJoin methods. These methods let you concatenate strings for building a file or directory path.

    - the different betweeen adding and append the `adding` is creating file from 0 and the and add the lines or the data, while the `append` just adding after the file is exist so we can say it is like editing.
    - and also with file class can do all of this adding and creating and appending.

- ## Read a file

    - The System.IO.BinaryWriter and System.IO.BinaryReader classes are used for writing and reading data other than character strings. The following example shows how to create an empty file stream, write data to it, and read data from it.
    - The example creates a file named "Test.data" and writes the integers 0 through 10 to it  
     in binary format.
     It then writes the contents of Test.data to the console with each integer on a separate line.


- ## things i want to know more about 

    - how to read and write inside any file easly and fast 
    - how to edit the data inside the file, how to append, adding.
    - know more about files and directoreis, the Asynchronous I/O operations also 
    - Compression how to deal with extracting files and find data and deal with it if it is avilable. 