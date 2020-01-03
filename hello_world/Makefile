NODENAME := hello_world
VERSION := 0.1.0

run:
	# iex -S mix
	iex --name "$(NODENAME)@127.0.0.1" --cookie "$(NODENAME)_cookie" -S mix

push:
	git add .
	git commit -m 'x'
	git push
