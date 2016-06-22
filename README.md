# logrotatewin // Peter's branch

I forked Ken's logrotate implementation because there are few functions that are not fitting into our use-case scenarios.
- Ability to provide relative path when specifying Olddir
- Ken's always compares to previous run when rotating, so the first run was never successful for me. I fixed it.
- If confpath is not provided Content\logrotate.conf will be used by default.


# Original readme:
This is a Windows implementation of the logrotate utility found in Linux platforms. The goal is to use the same command line parameters and files as the Linux version.

LogRotate for Windows
Written by Ken Salter (C) 2012-2015

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Program description:

This is a port of the logrotate utility available for Linux.  See the Wiki for more notes.

https://sourceforge.net/projects/logrotatewin/

Requirements:

.NET Framework v2.0 or better
