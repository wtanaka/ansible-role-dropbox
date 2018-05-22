[![Build Status](https://travis-ci.org/wtanaka/ansible-role-dropbox.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-dropbox)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-dropbox.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-dropbox)

wtanaka.dropbox
===============

This ansible role installs dropbox.

This includes some logic from the role created by Julien DAUPHANT, which
are Copyright (c) 2014, Julien DAUPHANT and are subject to the
two-clause BSD license:

* Redistributions of source code must retain the above copyright notice, this
  list of conditions and the following disclaimer.

* Redistributions in binary form must reproduce the above copyright notice,
  this list of conditions and the following disclaimer in the documentation
  and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

The other code is released under GPLv2 copyright Wesley Tanaka.

Example Playbook
----------------

    - hosts: all
      roles:
         - wtanaka.dropbox

License
-------

GPLv2
