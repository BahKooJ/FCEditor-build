# FCEditor 0.0.0a
 
Open mission files via File/Open
Close mission files via File/Close

FCEditor displays all chunks in order that they apear in the file. 

Each file has a generic export, import, delete, and insert option.

Known file formats will have specific previews for viewing content, use the content export or import to export or import the formatted file. Using the generic options will only apply to the raw files, and not the formatted file.

For importing, select the file name, and select "remove FILLs". After all importing is done, be sure to add fills back, otherwise future cop will not be able to read it

Importing any sound (Cwav, snds, music) must be of wav format. For them to work properly make sure the wav file has the correct formatting acording to original data:
Cwav - bits = 16, samplerate = 22050
snds - bits = 8, samplerate = 22050
music - bits = 8, samplerate = 14212
