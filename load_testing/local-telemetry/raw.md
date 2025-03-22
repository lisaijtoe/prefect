$r=[int](random -Mi 1e5 -Ma 1e6);$f="$env:tmp\c.txt";sc $f "Your Verification code> $r";notepad $f
