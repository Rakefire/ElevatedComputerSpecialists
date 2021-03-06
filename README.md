I've setup a basic git repo for the ECS static site with Jekyll. Here are the deets:

Created a github org to hand over when complete: <https://github.com/ElevatedComputerSpecialists>

Repo for the jekyll site: <https://github.com/ElevatedComputerSpecialists/ElevatedComputerSpecialists.github.io>

The site is currently accessible at: <http://elevatedcomputerspecialists.github.io/>

To get started from the command line:

* `git clone git@github.com:ElevatedComputerSpecialists/ElevatedComputerSpecialists.github.io.git`
* `cd ElevatedComputerSpecialists.github.io`
* `gem install bundler`
* `bundle install # Note: may need to install inconv libraries for nokogri`

# Start Server

* `c wd /path/to/repo`
* `bin/serve # This will start jekyll and serve it locally`
* Browse to http://0.0.0.0:4000/

# Do work...

* `git add --all`
* `git commit -am "Helpful Description of what you did"`
* `git push origin master`

# Profit!

Checkout the jekyll docs on how to start modifying the site: <http://jekyllrb.com/docs/structure/>
