# MacShairport
[Shairport](https://github.com/albertz/shairport) is this great thing that lets a computer pretend to be an Airport Express speaker. So that means one computer can send audio from iTunes to be played on another computer. Awesome, right? Except the Shairport server itself is written in Perl and has dependencies that make it hard for normal people to use and install.

## So what?
MacShairport is a native re-implementation of Shairport for Mac. That means any Mac user could download a build and run it on their computer without having to worry about Perl modules and dependencies. Win.

## Does it work?
Well... kinda. It's not quite done. Right now it will advertise itself as a speaker and do all the handshaking to let another computer's iTunes send it music to play. That's arguably the hard part. What remains now is launching hairtunes to accept the stream from the other iTunes.

## How can I help?
Like I mentioned above, the shairtunes server is written in Perl. I have practically zero experience with Perl, but I've been copying the implementation from [shairport.pl](https://github.com/albertz/shairport/blob/master/shairport.pl). So if you want to help, just dive right now.