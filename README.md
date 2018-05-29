# gdx2json
Reads GAMS (gdx) database files and outputs a json formatted file.  Will read all contents of a gdx file including -- sets, parameters (including scalars), variables (.lo, .l, .up, .m, .scale), and equations (.lo, .l, .up, .m, .scale).  Output is a json formatted file.

# Requirements
Python 3
GAMS API (high level)


# Use
python3 --in=gdxfilename.gdx

Output file name will be 'gdxfilename.json'.
