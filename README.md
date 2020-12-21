# Design-Pattern-Adapter-Class

Object adapter rely on object composition,while class adapters rely on inheritance.

Swing: you determine if a check box is checked using the isSelected method.
AWT check boxes don't support isSelected;the AWT method is getState.

Adapt the getState to isSelected!
