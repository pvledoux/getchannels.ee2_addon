#Pvl GetChannel version 0.2

GetChannel is a ExpressionEngine plugin that returns the list of channels.
The list can be limited to channels authorized to the current loggin user.

##Syntax

	{exp:getchannels [site_id="site_id"] [restricted="no"]}
		{channel_id}
		{channel_name}
		{channel_title}
		{total_entries}
	{/exp:getchannels}
	

##Parameters

<table>
<tr>
	<td><b>site_id="1"</b></td>
	<td>Optional (default: 1) In a MSM (Multiple Site Manager) your can specify which site will be used to return the channels</td>
</tr>
<tr>
	<td><b>restricted="yes|no"</b></td>
	<td>Optional (default: yes) Only get logged in member authorized channels</td>
</tr>
</table>


##Licence
Copyright (c) 2012 Pv Ledoux All rights reserved.

Redistribution and use in source and binary forms, with or without modification, are permitted provided that the following conditions are met:

* Redistributions of source code must retain the above copyright notice, this list of conditions and the following disclaimer.
* Redistributions in binary form must reproduce the above copyright notice, this list of conditions and the following disclaimer in the documentation and/or other materials provided with the distribution.
* Neither the name of the <organization> nor the names of its contributors may be used to endorse or promote products derived from this software without specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL <COPYRIGHT HOLDER> BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.