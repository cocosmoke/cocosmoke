Last login: Tue Jan 16 23:21:20 on ttys000
codyroberts@Codys-iMac ~ % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password)...
Password:
==> This script will install:
/usr/local/bin/brew
/usr/local/share/doc/homebrew
/usr/local/share/man/man1/brew.1
/usr/local/share/zsh/site-functions/_brew
/usr/local/etc/bash_completion.d/brew
/usr/local/Homebrew

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /usr/sbin/chown -R codyroberts:admin /usr/local/Homebrew
==> Downloading and installing Homebrew...
HEAD is now at 8c805d7fe Merge pull request #16489 from Homebrew/dependabot/bundler/Library/Homebrew/concurrent-ruby-1.2.3
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run these two commands in your terminal to add Homebrew to your PATH:
    (echo; echo 'eval "$(/usr/local/bin/brew shellenv)"') >> /Users/codyroberts/.zprofile
    eval "$(/usr/local/bin/brew shellenv)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh

codyroberts@Codys-iMac ~ % brew install cmake protobuf rust python@3.10 git wget
Warning: Treating cmake as a formula. For the cask, use homebrew/cask/cmake
Warning: python@3.10 3.10.13_1 is already installed and up-to-date.
To reinstall 3.10.13_1, run:
  brew reinstall python@3.10
==> Downloading https://ghcr.io/v2/homebrew/core/cmake/manifests/3.28.1
######################################################################### 100.0%
==> Fetching cmake
==> Downloading https://ghcr.io/v2/homebrew/core/cmake/blobs/sha256:cf732d075da2
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/protobuf/manifests/25.1-1
######################################################################### 100.0%
==> Fetching dependencies for protobuf: abseil and jsoncpp
==> Downloading https://ghcr.io/v2/homebrew/core/abseil/manifests/20230802.1
######################################################################### 100.0%
==> Fetching abseil
==> Downloading https://ghcr.io/v2/homebrew/core/abseil/blobs/sha256:4b0d382639c
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/jsoncpp/manifests/1.9.5
######################################################################### 100.0%
==> Fetching jsoncpp
==> Downloading https://ghcr.io/v2/homebrew/core/jsoncpp/blobs/sha256:68fe5f2b8a
######################################################################### 100.0%
==> Fetching protobuf
==> Downloading https://ghcr.io/v2/homebrew/core/protobuf/blobs/sha256:49998369e
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/rust/manifests/1.75.0
######################################################################### 100.0%
==> Fetching dependencies for rust: libssh2, libgit2, python@3.12, z3, lz4, zstd, llvm and pkg-config
==> Downloading https://ghcr.io/v2/homebrew/core/libssh2/manifests/1.11.0_1
######################################################################### 100.0%
==> Fetching libssh2
==> Downloading https://ghcr.io/v2/homebrew/core/libssh2/blobs/sha256:71b9199fd2
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libgit2/manifests/1.7.1
######################################################################### 100.0%
==> Fetching libgit2
==> Downloading https://ghcr.io/v2/homebrew/core/libgit2/blobs/sha256:fdf652b3f2
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.12/manifests/3.12.1
######################################################################### 100.0%
==> Fetching python@3.12
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.12/blobs/sha256:346994
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/z3/manifests/4.12.4
######################################################################### 100.0%
==> Fetching z3
==> Downloading https://ghcr.io/v2/homebrew/core/z3/blobs/sha256:0fab3d037ce7eac
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/lz4/manifests/1.9.4
######################################################################### 100.0%
==> Fetching lz4
==> Downloading https://ghcr.io/v2/homebrew/core/lz4/blobs/sha256:6a911ee2a3ea07
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/zstd/manifests/1.5.5-1
######################################################################### 100.0%
==> Fetching zstd
==> Downloading https://ghcr.io/v2/homebrew/core/zstd/blobs/sha256:f74c7a0b93a21
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/llvm/manifests/17.0.6
######################################################################### 100.0%
==> Fetching llvm
==> Downloading https://ghcr.io/v2/homebrew/core/llvm/blobs/sha256:e7d1f94464e3b
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/pkg-config/manifests/0.29.2_3
######################################################################### 100.0%
==> Fetching pkg-config
==> Downloading https://ghcr.io/v2/homebrew/core/pkg-config/blobs/sha256:c44b154
######################################################################### 100.0%
==> Fetching rust
==> Downloading https://ghcr.io/v2/homebrew/core/rust/blobs/sha256:f8f5fdc384795
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/git/manifests/2.43.0
######################################################################### 100.0%
==> Fetching dependencies for git: gettext and pcre2
==> Downloading https://ghcr.io/v2/homebrew/core/gettext/manifests/0.22.4
######################################################################### 100.0%
==> Fetching gettext
==> Downloading https://ghcr.io/v2/homebrew/core/gettext/blobs/sha256:1fd9c7c657
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/pcre2/manifests/10.42
######################################################################### 100.0%
==> Fetching pcre2
==> Downloading https://ghcr.io/v2/homebrew/core/pcre2/blobs/sha256:7f414ed9d561
######################################################################### 100.0%
==> Fetching git
==> Downloading https://ghcr.io/v2/homebrew/core/git/blobs/sha256:e1b880d4eb4191
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/wget/manifests/1.21.4
######################################################################### 100.0%
==> Fetching dependencies for wget: libunistring and libidn2
==> Downloading https://ghcr.io/v2/homebrew/core/libunistring/manifests/1.1
######################################################################### 100.0%
==> Fetching libunistring
==> Downloading https://ghcr.io/v2/homebrew/core/libunistring/blobs/sha256:10dbd
######################################################################### 100.0%
==> Downloading https://ghcr.io/v2/homebrew/core/libidn2/manifests/2.3.4_1-1
######################################################################### 100.0%
==> Fetching libidn2
==> Downloading https://ghcr.io/v2/homebrew/core/libidn2/blobs/sha256:322028f5aa
######################################################################### 100.0%
==> Fetching wget
==> Downloading https://ghcr.io/v2/homebrew/core/wget/blobs/sha256:f1d0f59e9cd58
######################################################################### 100.0%
==> Pouring cmake--3.28.1.ventura.bottle.tar.gz
==> Caveats
To install the CMake documentation, run:
  brew install cmake-docs

Emacs Lisp files have been installed to:
  /usr/local/share/emacs/site-lisp/cmake
==> Summary
🍺  /usr/local/Cellar/cmake/3.28.1: 3,329 files, 59.7MB
==> Running `brew cleanup cmake`...
Disable this behaviour by setting HOMEBREW_NO_INSTALL_CLEANUP.
Hide these hints with HOMEBREW_NO_ENV_HINTS (see `man brew`).
==> Installing dependencies for protobuf: abseil and jsoncpp
==> Installing protobuf dependency: abseil
==> Downloading https://ghcr.io/v2/homebrew/core/abseil/manifests/20230802.1
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/84a39e6e67feb436daaebbb0ac432f7f7b69e013150c845340427a38f1523068--abseil-20230802.1.bottle_manifest.json
==> Pouring abseil--20230802.1.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/abseil/20230802.1: 741 files, 9.3MB
==> Installing protobuf dependency: jsoncpp
==> Downloading https://ghcr.io/v2/homebrew/core/jsoncpp/manifests/1.9.5
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/61fb7cb7b03533b1884f5de81b3b44a2e6edc058e8a87de7be462305888460c0--jsoncpp-1.9.5.bottle_manifest.json
==> Pouring jsoncpp--1.9.5.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/jsoncpp/1.9.5: 18 files, 282.2KB
==> Installing protobuf
==> Pouring protobuf--25.1.ventura.bottle.1.tar.gz
==> Caveats
Emacs Lisp files have been installed to:
  /usr/local/share/emacs/site-lisp/protobuf
==> Summary
🍺  /usr/local/Cellar/protobuf/25.1: 402 files, 13.4MB
==> Running `brew cleanup protobuf`...
==> Installing dependencies for rust: libssh2, libgit2, python@3.12, z3, lz4, zstd, llvm and pkg-config
==> Installing rust dependency: libssh2
==> Downloading https://ghcr.io/v2/homebrew/core/libssh2/manifests/1.11.0_1
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/48ca0c7785b21630a4817c59b72205609ccb0575e7abc64d64af2e61a60b5b0a--libssh2-1.11.0_1.bottle_manifest.json
==> Pouring libssh2--1.11.0_1.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/libssh2/1.11.0_1: 197 files, 1.1MB
==> Installing rust dependency: libgit2
==> Downloading https://ghcr.io/v2/homebrew/core/libgit2/manifests/1.7.1
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/1b309c0d2e280bfce9151bfc58b4b2d18986fd471ee65e4585b6dc341fe347da--libgit2-1.7.1.bottle_manifest.json
==> Pouring libgit2--1.7.1.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/libgit2/1.7.1: 104 files, 4.4MB
==> Installing rust dependency: python@3.12
==> Downloading https://ghcr.io/v2/homebrew/core/python/3.12/manifests/3.12.1
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/b13664874124f24d86fbf576412860426d44202df0a3a858c00900d566c12ea4--python@3.12-3.12.1.bottle_manifest.json
==> Pouring python@3.12--3.12.1.ventura.bottle.tar.gz
==> /usr/local/Cellar/python@3.12/3.12.1/bin/python3.12 -Im ensurepip
==> /usr/local/Cellar/python@3.12/3.12.1/bin/python3.12 -Im pip install -v --no-
🍺  /usr/local/Cellar/python@3.12/3.12.1: 3,223 files, 63.4MB
==> Installing rust dependency: z3
==> Downloading https://ghcr.io/v2/homebrew/core/z3/manifests/4.12.4
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/c1b2d802548fa65fcdf4e55294c7a6aa470dbaf7b7228933fba53d563085f6fc--z3-4.12.4.bottle_manifest.json
==> Pouring z3--4.12.4.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/z3/4.12.4: 118 files, 31.6MB
==> Installing rust dependency: lz4
==> Downloading https://ghcr.io/v2/homebrew/core/lz4/manifests/1.9.4
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/379e59b981667f9585b33a2ff318769d8edca3ce6fd2e9a67ed291ae3e0cc872--lz4-1.9.4.bottle_manifest.json
==> Pouring lz4--1.9.4.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/lz4/1.9.4: 22 files, 684.9KB
==> Installing rust dependency: zstd
==> Downloading https://ghcr.io/v2/homebrew/core/zstd/manifests/1.5.5-1
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/fc13698599720a53800064b40cddd854399651cf8760d9b0e46092f2e8da701a--zstd-1.5.5-1.bottle_manifest.json
==> Pouring zstd--1.5.5.ventura.bottle.1.tar.gz
🍺  /usr/local/Cellar/zstd/1.5.5: 31 files, 2.3MB
==> Installing rust dependency: llvm
==> Downloading https://ghcr.io/v2/homebrew/core/llvm/manifests/17.0.6
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/df3adcb2abbae1018057d5f34f8130edb2081998d41c5501dfcc91fb69b24ac9--llvm-17.0.6.bottle_manifest.json
==> Pouring llvm--17.0.6.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/llvm/17.0.6: 7,207 files, 1.8GB
==> Installing rust dependency: pkg-config
==> Downloading https://ghcr.io/v2/homebrew/core/pkg-config/manifests/0.29.2_3
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/ac691fc7ab8ecffba32a837e7197101d271474a3a84cfddcc30c9fd6763ab3c6--pkg-config-0.29.2_3.bottle_manifest.json
==> Pouring pkg-config--0.29.2_3.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/pkg-config/0.29.2_3: 11 files, 656KB
==> Installing rust
==> Pouring rust--1.75.0.ventura.bottle.tar.gz
==> Caveats
zsh completions have been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/rust/1.75.0: 39,133 files, 864.8MB
==> Running `brew cleanup rust`...
==> Installing dependencies for git: gettext and pcre2
==> Installing git dependency: gettext
==> Downloading https://ghcr.io/v2/homebrew/core/gettext/manifests/0.22.4
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/3ceb9457127eaa7378dd80ed256098ffb391e2350069becb25cfe2a14f0b7d6d--gettext-0.22.4.bottle_manifest.json
==> Pouring gettext--0.22.4.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/gettext/0.22.4: 2,042 files, 23.7MB
==> Installing git dependency: pcre2
==> Downloading https://ghcr.io/v2/homebrew/core/pcre2/manifests/10.42
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/6a53794fcaabc5cc5e05b19c02ca9c4c5f2cb9a4d65a5790a6841146465b040f--pcre2-10.42.bottle_manifest.json
==> Pouring pcre2--10.42.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/pcre2/10.42: 230 files, 6.3MB
==> Installing git
==> Pouring git--2.43.0.ventura.bottle.tar.gz
==> Caveats
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.

zsh completions and functions have been installed to:
  /usr/local/share/zsh/site-functions
==> Summary
🍺  /usr/local/Cellar/git/2.43.0: 1,638 files, 49.7MB
==> Running `brew cleanup git`...
==> Installing dependencies for wget: libunistring and libidn2
==> Installing wget dependency: libunistring
==> Downloading https://ghcr.io/v2/homebrew/core/libunistring/manifests/1.1
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/a34801f1ad5800ba51b2b3951d82a913ccf0641982f86b02df2f0aa182535055--libunistring-1.1.bottle_manifest.json
==> Pouring libunistring--1.1.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/libunistring/1.1: 56 files, 5MB
==> Installing wget dependency: libidn2
==> Downloading https://ghcr.io/v2/homebrew/core/libidn2/manifests/2.3.4_1-1
Already downloaded: /Users/codyroberts/Library/Caches/Homebrew/downloads/03ad193177f4e7d05ee2ed19a455028cb5fbf7ea1a812d88f18f5e9e8b4a4d43--libidn2-2.3.4_1-1.bottle_manifest.json
==> Pouring libidn2--2.3.4_1.ventura.bottle.1.tar.gz
🍺  /usr/local/Cellar/libidn2/2.3.4_1: 79 files, 1003.3KB
==> Installing wget
==> Pouring wget--1.21.4.ventura.bottle.tar.gz
🍺  /usr/local/Cellar/wget/1.21.4: 91 files, 4.4MB
==> Running `brew cleanup wget`...
==> Caveats
==> cmake
To install the CMake documentation, run:
  brew install cmake-docs

Emacs Lisp files have been installed to:
  /usr/local/share/emacs/site-lisp/cmake
==> protobuf
Emacs Lisp files have been installed to:
  /usr/local/share/emacs/site-lisp/protobuf
==> rust
zsh completions have been installed to:
  /usr/local/share/zsh/site-functions
==> git
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.

zsh completions and functions have been installed to:
  /usr/local/share/zsh/site-functions
codyroberts@Codys-iMac ~ % git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui
Cloning into 'stable-diffusion-webui'...
remote: Enumerating objects: 30486, done.
remote: Counting objects: 100% (175/175), done.
remote: Compressing objects: 100% (100/100), done.
remote: Total 30486 (delta 99), reused 125 (delta 75), pack-reused 30311
Receiving objects: 100% (30486/30486), 33.41 MiB | 12.73 MiB/s, done.
Resolving deltas: 100% (21344/21344), done.
codyroberts@Codys-iMac ~ % open .
codyroberts@Codys-iMac ~ % cd stable-diffusion-webui 
codyroberts@Codys-iMac stable-diffusion-webui % ./webui.sh 

################################################################
Install script for stable-diffusion + Web UI
Tested on Debian 11 (Bullseye), Fedora 34+ and openSUSE Leap 15.4 or newer.
################################################################

################################################################
Running on codyroberts user
################################################################

################################################################
Repo already cloned, using it as install directory
################################################################

################################################################
Create and activate python venv
################################################################

################################################################
Launching launch.py...
################################################################
Python 3.10.13 (main, Nov  1 2023, 17:29:04) [Clang 14.0.3 (clang-1403.0.22.14.1)]
Version: v1.7.0
Commit hash: cf2772fab0af5573da775e7437e6acdca424f26e
Installing torch and torchvision
Collecting torch==2.0.1
  Using cached torch-2.0.1-cp310-none-macosx_10_9_x86_64.whl (143.4 MB)
Collecting torchvision==0.15.2
  Using cached torchvision-0.15.2-cp310-cp310-macosx_10_9_x86_64.whl (1.5 MB)
Collecting filelock (from torch==2.0.1)
  Using cached filelock-3.13.1-py3-none-any.whl.metadata (2.8 kB)
Collecting typing-extensions (from torch==2.0.1)
  Using cached typing_extensions-4.9.0-py3-none-any.whl.metadata (3.0 kB)
Collecting sympy (from torch==2.0.1)
  Using cached sympy-1.12-py3-none-any.whl (5.7 MB)
Collecting networkx (from torch==2.0.1)
  Using cached networkx-3.2.1-py3-none-any.whl.metadata (5.2 kB)
Collecting jinja2 (from torch==2.0.1)
  Using cached Jinja2-3.1.3-py3-none-any.whl.metadata (3.3 kB)
Collecting numpy (from torchvision==0.15.2)
  Using cached numpy-1.26.3-cp310-cp310-macosx_10_9_x86_64.whl.metadata (61 kB)
Collecting requests (from torchvision==0.15.2)
  Using cached requests-2.31.0-py3-none-any.whl.metadata (4.6 kB)
Collecting pillow!=8.3.*,>=5.3.0 (from torchvision==0.15.2)
  Using cached pillow-10.2.0-cp310-cp310-macosx_10_10_x86_64.whl.metadata (9.7 kB)
Collecting MarkupSafe>=2.0 (from jinja2->torch==2.0.1)
  Using cached MarkupSafe-2.1.3-cp310-cp310-macosx_10_9_x86_64.whl.metadata (3.0 kB)
Collecting charset-normalizer<4,>=2 (from requests->torchvision==0.15.2)
  Using cached charset_normalizer-3.3.2-cp310-cp310-macosx_10_9_x86_64.whl.metadata (33 kB)
Collecting idna<4,>=2.5 (from requests->torchvision==0.15.2)
  Using cached idna-3.6-py3-none-any.whl.metadata (9.9 kB)
Collecting urllib3<3,>=1.21.1 (from requests->torchvision==0.15.2)
  Using cached urllib3-2.1.0-py3-none-any.whl.metadata (6.4 kB)
Collecting certifi>=2017.4.17 (from requests->torchvision==0.15.2)
  Using cached certifi-2023.11.17-py3-none-any.whl.metadata (2.2 kB)
Collecting mpmath>=0.19 (from sympy->torch==2.0.1)
  Using cached mpmath-1.3.0-py3-none-any.whl (536 kB)
Using cached pillow-10.2.0-cp310-cp310-macosx_10_10_x86_64.whl (3.5 MB)
Using cached filelock-3.13.1-py3-none-any.whl (11 kB)
Using cached Jinja2-3.1.3-py3-none-any.whl (133 kB)
Using cached networkx-3.2.1-py3-none-any.whl (1.6 MB)
Using cached numpy-1.26.3-cp310-cp310-macosx_10_9_x86_64.whl (20.6 MB)
Using cached requests-2.31.0-py3-none-any.whl (62 kB)
Using cached typing_extensions-4.9.0-py3-none-any.whl (32 kB)
Using cached certifi-2023.11.17-py3-none-any.whl (162 kB)
Using cached charset_normalizer-3.3.2-cp310-cp310-macosx_10_9_x86_64.whl (122 kB)
Using cached idna-3.6-py3-none-any.whl (61 kB)
Using cached MarkupSafe-2.1.3-cp310-cp310-macosx_10_9_x86_64.whl (13 kB)
Using cached urllib3-2.1.0-py3-none-any.whl (104 kB)
Installing collected packages: mpmath, urllib3, typing-extensions, sympy, pillow, numpy, networkx, MarkupSafe, idna, filelock, charset-normalizer, certifi, requests, jinja2, torch, torchvision
Successfully installed MarkupSafe-2.1.3 certifi-2023.11.17 charset-normalizer-3.3.2 filelock-3.13.1 idna-3.6 jinja2-3.1.3 mpmath-1.3.0 networkx-3.2.1 numpy-1.26.3 pillow-10.2.0 requests-2.31.0 sympy-1.12 torch-2.0.1 torchvision-0.15.2 typing-extensions-4.9.0 urllib3-2.1.0

[notice] A new release of pip is available: 23.3.1 -> 23.3.2
[notice] To update, run: pip install --upgrade pip
Installing clip
Installing open_clip
Cloning Stable Diffusion into /Users/codyroberts/stable-diffusion-webui/repositories/stable-diffusion-stability-ai...
Cloning into '/Users/codyroberts/stable-diffusion-webui/repositories/stable-diffusion-stability-ai'...
remote: Enumerating objects: 580, done.
remote: Counting objects: 100% (580/580), done.
remote: Compressing objects: 100% (311/311), done.
remote: Total 580 (delta 279), reused 452 (delta 248), pack-reused 0
Receiving objects: 100% (580/580), 73.44 MiB | 10.55 MiB/s, done.
Resolving deltas: 100% (279/279), done.
Cloning Stable Diffusion XL into /Users/codyroberts/stable-diffusion-webui/repositories/generative-models...
Cloning into '/Users/codyroberts/stable-diffusion-webui/repositories/generative-models'...
remote: Enumerating objects: 860, done.
remote: Counting objects: 100% (513/513), done.
remote: Compressing objects: 100% (244/244), done.
remote: Total 860 (delta 365), reused 308 (delta 265), pack-reused 347
Receiving objects: 100% (860/860), 42.67 MiB | 11.55 MiB/s, done.
Resolving deltas: 100% (436/436), done.
Cloning K-diffusion into /Users/codyroberts/stable-diffusion-webui/repositories/k-diffusion...
Cloning into '/Users/codyroberts/stable-diffusion-webui/repositories/k-diffusion'...
remote: Enumerating objects: 1329, done.
remote: Counting objects: 100% (611/611), done.
remote: Compressing objects: 100% (81/81), done.
remote: Total 1329 (delta 568), reused 538 (delta 530), pack-reused 718
Receiving objects: 100% (1329/1329), 239.04 KiB | 2.95 MiB/s, done.
Resolving deltas: 100% (931/931), done.
Cloning CodeFormer into /Users/codyroberts/stable-diffusion-webui/repositories/CodeFormer...
Cloning into '/Users/codyroberts/stable-diffusion-webui/repositories/CodeFormer'...
remote: Enumerating objects: 594, done.
remote: Counting objects: 100% (245/245), done.
remote: Compressing objects: 100% (90/90), done.
remote: Total 594 (delta 176), reused 170 (delta 155), pack-reused 349
Receiving objects: 100% (594/594), 17.30 MiB | 10.87 MiB/s, done.
Resolving deltas: 100% (287/287), done.
Cloning BLIP into /Users/codyroberts/stable-diffusion-webui/repositories/BLIP...
Cloning into '/Users/codyroberts/stable-diffusion-webui/repositories/BLIP'...
remote: Enumerating objects: 277, done.
remote: Counting objects: 100% (165/165), done.
remote: Compressing objects: 100% (30/30), done.
remote: Total 277 (delta 137), reused 136 (delta 135), pack-reused 112
Receiving objects: 100% (277/277), 7.03 MiB | 7.08 MiB/s, done.
Resolving deltas: 100% (152/152), done.
Installing requirements for CodeFormer
Installing requirements
Launching Web UI with arguments: --skip-torch-cuda-test --upcast-sampling --no-half-vae --use-cpu interrogate
no module 'xformers'. Processing without...
no module 'xformers'. Processing without...
No module 'xformers'. Proceeding without it.
Style database not found: /Users/codyroberts/stable-diffusion-webui/styles.csv
Warning: caught exception 'Torch not compiled with CUDA enabled', memory monitor disabled
Calculating sha256 for /Users/codyroberts/stable-diffusion-webui/models/Stable-diffusion/v1-5-pruned.ckpt: Running on local URL:  http://127.0.0.1:7860

To create a public link, set `share=True` in `launch()`.
Startup time: 128.3s (prepare environment: 87.9s, import torch: 14.5s, import gradio: 4.7s, setup paths: 8.8s, initialize shared: 0.3s, other imports: 10.3s, setup codeformer: 0.1s, load scripts: 0.9s, create ui: 0.5s, gradio launch: 0.3s).
e1441589a6f3c5a53f5f54d0975a18a7feb7cdf0b0dee276dfc3331ae376a053
Loading weights [e1441589a6] from /Users/codyroberts/stable-diffusion-webui/models/Stable-diffusion/v1-5-pruned.ckpt
Creating model from config: /Users/codyroberts/stable-diffusion-webui/configs/v1-inference.yaml
Applying attention optimization: sub-quadratic... done.
Model loaded in 28.0s (calculate hash: 16.6s, load weights from disk: 4.7s, create model: 0.8s, apply weights to model: 4.2s, apply half(): 0.4s, calculate empty prompt: 1.0s).
-[MTLIOAccelCommandBuffer validate]:207: failed assertion `commit an already committed command buffer'
./webui.sh: line 256: 34023 Abort trap: 6           "${python_cmd}" -u "${LAUNCH_SCRIPT}" "$@"
codyroberts@Codys-iMac stable-diffusion-webui % ./webui.sh     

################################################################
Install script for stable-diffusion + Web UI
Tested on Debian 11 (Bullseye), Fedora 34+ and openSUSE Leap 15.4 or newer.
################################################################

################################################################
Running on codyroberts user
################################################################

################################################################
Repo already cloned, using it as install directory
################################################################

################################################################
Create and activate python venv
################################################################

################################################################
Launching launch.py...
################################################################
Python 3.10.13 (main, Nov  1 2023, 17:29:04) [Clang 14.0.3 (clang-1403.0.22.14.1)]
Version: v1.7.0
Commit hash: cf2772fab0af5573da775e7437e6acdca424f26e
Launching Web UI with arguments: --skip-torch-cuda-test --upcast-sampling --no-half-vae --use-cpu interrogate
no module 'xformers'. Processing without...
no module 'xformers'. Processing without...
No module 'xformers'. Proceeding without it.
Style database not found: /Users/codyroberts/stable-diffusion-webui/styles.csv
Warning: caught exception 'Torch not compiled with CUDA enabled', memory monitor disabled
Loading weights [e1441589a6] from /Users/codyroberts/stable-diffusion-webui/models/Stable-diffusion/v1-5-pruned.ckpt
Running on local URL:  http://127.0.0.1:7860

To create a public link, set `share=True` in `launch()`.
Startup time: 7.4s (prepare environment: 0.1s, import torch: 2.8s, import gradio: 1.0s, setup paths: 0.9s, initialize shared: 0.2s, other imports: 0.7s, load scripts: 0.8s, create ui: 0.7s, gradio launch: 0.3s).
Loading weights [e1441589a6] from /Users/codyroberts/stable-diffusion-webui/models/Stable-diffusion/v1-5-pruned.ckpt
Creating model from config: /Users/codyroberts/stable-diffusion-webui/configs/v1-inference.yaml
Creating model from config: /Users/codyroberts/stable-diffusion-webui/configs/v1-inference.yaml
Applying attention optimization: sub-quadratic... done.
Model loaded in 21.6s (load weights from disk: 9.7s, create model: 0.4s, apply weights to model: 9.8s, apply half(): 0.6s, move model to device: 0.1s, calculate empty prompt: 1.0s).
changing setting sd_model_checkpoint to v1-5-pruned.ckpt [e1441589a6]: RuntimeError
Traceback (most recent call last):
  File "/Users/codyroberts/stable-diffusion-webui/modules/options.py", line 146, in set
    option.onchange()
  File "/Users/codyroberts/stable-diffusion-webui/modules/call_queue.py", line 13, in f
    res = func(*args, **kwargs)
  File "/Users/codyroberts/stable-diffusion-webui/modules/initialize_util.py", line 174, in <lambda>
    shared.opts.onchange("sd_model_checkpoint", wrap_queued_call(lambda: sd_models.reload_model_weights()), call=False)
  File "/Users/codyroberts/stable-diffusion-webui/modules/sd_models.py", line 783, in reload_model_weights
    load_model(checkpoint_info, already_loaded_state_dict=state_dict)
  File "/Users/codyroberts/stable-diffusion-webui/modules/sd_models.py", line 658, in load_model
    load_model_weights(sd_model, checkpoint_info, state_dict, timer)
  File "/Users/codyroberts/stable-diffusion-webui/modules/sd_models.py", line 375, in load_model_weights
    model.load_state_dict(state_dict, strict=False)
  File "/Users/codyroberts/stable-diffusion-webui/modules/sd_disable_initialization.py", line 223, in <lambda>
    module_load_state_dict = self.replace(torch.nn.Module, 'load_state_dict', lambda *args, **kwargs: load_state_dict(module_load_state_dict, *args, **kwargs))
  File "/Users/codyroberts/stable-diffusion-webui/modules/sd_disable_initialization.py", line 221, in load_state_dict
    original(module, state_dict, strict=strict)
  File "/Users/codyroberts/stable-diffusion-webui/modules/sd_disable_initialization.py", line 223, in <lambda>
    module_load_state_dict = self.replace(torch.nn.Module, 'load_state_dict', lambda *args, **kwargs: load_state_dict(module_load_state_dict, *args, **kwargs))
  File "/Users/codyroberts/stable-diffusion-webui/modules/sd_disable_initialization.py", line 221, in load_state_dict
    original(module, state_dict, strict=strict)
  File "/Users/codyroberts/stable-diffusion-webui/venv/lib/python3.10/site-packages/torch/nn/modules/module.py", line 2041, in load_state_dict
    raise RuntimeError('Error(s) in loading state_dict for {}:\n\t{}'.format(
RuntimeError: Error(s) in loading state_dict for LatentDiffusion:
	While copying the parameter named "model.diffusion_model.output_blocks.4.0.emb_layers.1.weight", whose dimensions in the model are torch.Size([1280, 1280]) and whose dimensions in the checkpoint are torch.Size([1280, 1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.0.emb_layers.1.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.0.out_layers.0.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.0.out_layers.0.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.norm.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.norm.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.4.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.0.in_layers.0.weight", whose dimensions in the model are torch.Size([1920]) and whose dimensions in the checkpoint are torch.Size([1920]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.0.in_layers.0.bias", whose dimensions in the model are torch.Size([1920]) and whose dimensions in the checkpoint are torch.Size([1920]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.0.out_layers.0.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.0.out_layers.0.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.norm.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.norm.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.5.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.0.in_layers.0.weight", whose dimensions in the model are torch.Size([1920]) and whose dimensions in the checkpoint are torch.Size([1920]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.0.in_layers.0.bias", whose dimensions in the model are torch.Size([1920]) and whose dimensions in the checkpoint are torch.Size([1920]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.0.out_layers.0.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.0.out_layers.0.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.norm.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.norm.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.6.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.0.in_layers.0.weight", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.0.in_layers.0.bias", whose dimensions in the model are torch.Size([1280]) and whose dimensions in the checkpoint are torch.Size([1280]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.0.out_layers.0.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.0.out_layers.0.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.norm.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.norm.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.7.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.0.in_layers.0.weight", whose dimensions in the model are torch.Size([960]) and whose dimensions in the checkpoint are torch.Size([960]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.0.in_layers.0.bias", whose dimensions in the model are torch.Size([960]) and whose dimensions in the checkpoint are torch.Size([960]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.0.out_layers.0.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.0.out_layers.0.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.norm.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.norm.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.8.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.0.in_layers.0.weight", whose dimensions in the model are torch.Size([960]) and whose dimensions in the checkpoint are torch.Size([960]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.0.in_layers.0.bias", whose dimensions in the model are torch.Size([960]) and whose dimensions in the checkpoint are torch.Size([960]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.0.out_layers.0.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.0.out_layers.0.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.norm.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.norm.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.9.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.0.in_layers.0.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.0.in_layers.0.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.0.out_layers.0.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.0.out_layers.0.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.norm.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.norm.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.10.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.0.in_layers.0.weight", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.0.in_layers.0.bias", whose dimensions in the model are torch.Size([640]) and whose dimensions in the checkpoint are torch.Size([640]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.0.out_layers.0.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.0.out_layers.0.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.norm.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.norm.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.transformer_blocks.0.norm1.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.transformer_blocks.0.norm1.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.transformer_blocks.0.norm2.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.transformer_blocks.0.norm2.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.transformer_blocks.0.norm3.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.output_blocks.11.1.transformer_blocks.0.norm3.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.out.0.weight", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "model.diffusion_model.out.0.bias", whose dimensions in the model are torch.Size([320]) and whose dimensions in the checkpoint are torch.Size([320]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.0.norm1.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.0.norm1.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.0.norm2.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.0.norm2.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.1.norm1.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.1.norm1.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.1.norm2.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.0.block.1.norm2.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.0.norm1.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.0.norm1.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.0.norm2.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.0.norm2.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.1.norm1.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.1.norm1.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.1.norm2.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.1.block.1.norm2.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.0.norm1.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.0.norm1.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.0.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.0.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.1.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.1.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.1.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.2.block.1.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.0.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.0.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.0.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.0.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.1.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.1.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.1.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.down.3.block.1.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_1.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_1.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_1.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_1.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.attn_1.norm.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.attn_1.norm.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_2.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_2.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_2.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.mid.block_2.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.norm_out.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.encoder.norm_out.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_1.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_1.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_1.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_1.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.attn_1.norm.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.attn_1.norm.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_2.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_2.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_2.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.mid.block_2.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.0.norm1.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.0.norm1.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.0.norm2.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.0.norm2.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.1.norm1.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.1.norm1.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.1.norm2.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.1.norm2.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.2.norm1.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.2.norm1.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.2.norm2.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.0.block.2.norm2.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.0.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.0.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.0.norm2.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.0.norm2.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.1.norm1.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.1.norm1.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.1.norm2.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.1.norm2.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.2.norm1.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.2.norm1.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.2.norm2.weight", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.1.block.2.norm2.bias", whose dimensions in the model are torch.Size([256]) and whose dimensions in the checkpoint are torch.Size([256]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.0.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.0.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.0.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.0.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.1.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.1.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.1.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.1.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.2.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.2.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.2.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.2.block.2.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.0.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.0.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.0.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.0.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.1.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.1.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.1.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.1.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.2.norm1.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.2.norm1.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.2.norm2.weight", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.up.3.block.2.norm2.bias", whose dimensions in the model are torch.Size([512]) and whose dimensions in the checkpoint are torch.Size([512]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.norm_out.weight", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "first_stage_model.decoder.norm_out.bias", whose dimensions in the model are torch.Size([128]) and whose dimensions in the checkpoint are torch.Size([128]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.embeddings.position_ids", whose dimensions in the model are torch.Size([1, 77]) and whose dimensions in the checkpoint are torch.Size([1, 77]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.embeddings.token_embedding.weight", whose dimensions in the model are torch.Size([49408, 768]) and whose dimensions in the checkpoint are torch.Size([49408, 768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.embeddings.position_embedding.weight", whose dimensions in the model are torch.Size([77, 768]) and whose dimensions in the checkpoint are torch.Size([77, 768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.0.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.0.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.0.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.0.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.1.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.1.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.1.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.1.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.2.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.2.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.2.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.2.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.3.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.3.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.3.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.3.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.4.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.4.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.4.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.4.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.5.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.5.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.5.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.5.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.6.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.6.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.6.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.6.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.7.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.7.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.7.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.7.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.8.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.8.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.8.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.8.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.9.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.9.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.9.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.9.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.10.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.10.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.10.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.10.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.11.layer_norm1.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.11.layer_norm1.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.11.layer_norm2.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.encoder.layers.11.layer_norm2.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.final_layer_norm.weight", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).
	While copying the parameter named "cond_stage_model.transformer.text_model.final_layer_norm.bias", whose dimensions in the model are torch.Size([768]) and whose dimensions in the checkpoint are torch.Size([768]), an exception occurred : ('Cannot copy out of meta tensor; no data!',).

100%|███████████████████████████████████████████| 20/20 [00:11<00:00,  1.78it/s]
Total progress: 100%|███████████████████████████| 20/20 [00:09<00:00,  2.06it/s]
100%|███████████████████████████████████████████| 20/20 [00:09<00:00,  2.13it/s]
Total progress: 100%|███████████████████████████| 20/20 [00:09<00:00,  2.10it/s]
Total progress: 100%|███████████████████████████| 20/20 [00:09<00:00,  2.08it/s]
