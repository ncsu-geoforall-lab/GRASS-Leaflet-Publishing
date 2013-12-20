GRASS Leaflet Publishing
========================


License
-------

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 2 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

If you not have received a copy of the GNU General Public License along with this program, see http://www.gnu.org/licenses/.


3rd party code
--------------

The repository contains the Leaflet library distribution downloaded
from http://leafletjs.com/ (BSD 2-Clause license). It is contained in
the directory ``lib/leaflet``. This simplifies deployment on
some servers (``http`` versus ``https`` issue) and also it can make the
page a bit faster. However, it should be updated with a new release.
The included version is version 0.7 and Leaflet LICENSE file was added to
this directory.

The repository contains the Pavel Shramov's leaflet-plugins library downloaded
from https://github.com/shramov/leaflet-plugins (BSD 2-Clause license). It is
contained in the directory ``lib/shramov-leaflet-plugins``. This is almost
necessary for plugins and it simplifies deployment. However, it should
be updated with a new release. Subrepository is not used, source code
is used as is (without compiling or removing files).
The included version is version 1.0.0.

The repository contains the Leaflet.Coordinates library downloaded
from https://github.com/MrMufflon/Leaflet.Coordinates (CC BY). It is
contained in the directory ``lib/Leaflet.Coordinates``. This is almost
necessary for plugins and it simplifies deployment. However, it should
be updated with a new release. Subrepository is not used, source code
is used as is (without compiling or removing files).
The included version is version 0.1.3.

