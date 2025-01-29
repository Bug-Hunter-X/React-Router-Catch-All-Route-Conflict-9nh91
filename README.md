# React Router Catch-All Route Conflict

This repository demonstrates a common issue with React Router's catch-all route (`/*`). When placed before other routes, it can prevent those routes from matching correctly, leading to incorrect page rendering or unexpected behavior.  The solution involves reordering the routes within the `Routes` component.