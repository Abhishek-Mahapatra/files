class Solution{
public:
  node* removeNthfromeEnd(node* root, int n){
	if(root == NULL) return root;
	
	node* fast = root;
	node* slow = root;
	
	for(int i=1;i<=n+1;i++){
		fast = fast->next;
	}
	
	while(fast!=NULL){
		slow = slow->next;
		fast = fast->next;
	}
	
	slow->next = slow->next->next;
	
	return root;
 }
};
