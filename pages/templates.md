todo-ignore:: true

- milestone
  template:: milestone template
  template-including-parent:: false
	- milestone::
	  status:: planned, in-progress, complete 
	  start:: 
	  end::
- meeting minutes
  template:: meeting minutes
  template-including-parent:: false
	- title
	  tag:: meeting
	  project::
		- notetaker:: 
		  attendees::
		- agenda
			- TODO item1
			  assignee::
		- action items
			- TODO item1
			  DEADLINE:
			  assignee::