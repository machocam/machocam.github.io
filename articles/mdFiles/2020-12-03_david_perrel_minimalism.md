# Minimalism hides complexity

I just finished reading the [last essay](https://exercism.io/my/solutions/ce5a67ad792b4cb79ba3056006ba6028) of #DavidPerrel in which he criticises minimalism and the different forms it has taken now. Overall his article was not great IMO - he was superficial and failed to explain why Apple was the real thing and Blue Bottle was a copycat. 

In any case, what I do think is an interesting subject is the fact that minimalism tends to hide complexity. Yet hiding complexity doesn't make it go away. For example, I have a small alias which serves as a little script which saves me some time: 

```bash
alias nn='read -p "name of your note: " note_name && date_name=$(date +%F) && tot_name="${date_name}_${note_name}.md" && nvim ~/dox/vitz/notes/$tot_name'
```
Behind the command "nn" which seems *minimalist* there is complexity. What I think is more interesting than criticising minimalism is realizing that the simplicity of my little command often makes things more complex. If my command doesn't work for some reason, I will have to backtrack through various levels of abstraction to understand where the issue is. 

We feel the pain of this hidden complexity when our *simple* online services don't work - we are left with no recurse but restarting the machine and hoping for the best.

Next time you are using a seemingly *simple* or *minimalist* piece of technology; realize that you are in the mercy of all the complexity that simplicity is hiding. 

*Think of the hammer, now that is a minimalist piece of technology :)*
