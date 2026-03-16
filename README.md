
# Bell Entanglement simulation

This version to work with stupid go modules.

You need 3 windows to run this. Two windows run the agent program

<pre>
go run agent.go L
go run agent.go R
</pre>

Finally, you start the observer program, which represents the experimental process of releasing pairs and measuring them.

<pre>
go run observe.go
</pre>

Then go get coffee. The experiment will slowly churn through thousands of measurement events for all combinations of detector angles.

# NOTES

This is set up to simulate spin UP-DOWN pairs from a source to a detector which can be adjusted on each end in an axial geometry. The geometry is the key part to get the prediction of QM.

