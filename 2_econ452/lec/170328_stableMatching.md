2017-Mar-28 Tue 16h
# stable matching

In this document, all the $$ \geq \leq  $$ signs represents group symbols. 

$$
\left| \mu \left( w \right)  \right| = \left| \mu (F) \right|  
$$

Claim 1: 
$$
\mu ^{ F } \left( W \right) \in \mu ^{ w  } \left( w \right)
\\
\Longrightarrow \left| \mu ^{ F } \left( W \right)  \right| \geq \left| \mu ^{ w } \left( w \right)  \right| 
$$

$$
f \in \mu ^{ w } 
$$
implies 
$$
f \in \mu ^{ F } (w) 
$$
suppose some 
$$
f \in ^{ w } \left( w \right) \setminus \mu ^{ F } (w) 
$$
f is matched under 
$$
\mu^{ W }
$$
but alone/unmatched under $$ \mu ^{ F }  $$ . Since 
$$
\mu ^{ F } \geq \mu ^{ w } \left( f \right) 
$$ 
contradicting the stability of $$ \mu ^{ W }  $$ .

Claim 2: 
$$ 
\mu ^{ F } \left( F \right) \leq \mu ^{ w } \left( F \right) \\
\left| \mu ^{ F } \left( F \right)  \right| \leq \left| \mu ^{ w } \left( F \right)  \right| 
$$ 
$$
t \geq S \text{ and } t \leq S \Longrightarrow t=S 
$$


Claim 1 & 2:
$$
\begin{cases}
\mu ^{ W } = \mu ^{ W } (w), &\text{ }  \\
\mu ^{ F } = \mu ^{ W } (F), &\text{ }  \\ 
\end{cases}
$$


Let $$ \mu  $$ be an arbitrary stable matching. 

$$
\mu (w) \leq  \mu ^{ F } (w) \text{ - claim 1 } \\
\mu ^{ w } (f) \geq \mu (f) \text{ - claim 2 } 
$$

Since $$ \left| \mu (w) \right| = \left| \mu (f) \right|  $$ 
and $$ \left| \mu ^{ w } (f) \right| = \left| \mu ^{ F } (w) \right|  $$ 

$$
\mu (w) = \mu ^{ f } (w)\:\: \text{ i.e.   }  (=\mu ^{ w } (w))\\
\text{ and } \mu ^{ w } (f) = \mu (f) = \left(\mu ^{ F } (F)\right)
$$

## Proposition 4:

When preferences are strict, the common preferences of the two sides of the market are opposed on the set of stable matchings. If $$ \mu \text{ and } \mu ' $$ are two stable matchings, then all firms like $$\mu $$ at least as much as $$ \mu ' $$ if and only if all workers like $$ \mu ' $$ at least as much as $$ \mu  $$ .

## Corollary 5
When preferences are strict, the F-optimal matching is the worst stable matching for W and the W optimal matching is the worst for F.

### Case 1:
$$
\text{ If } i = \mu(i),\text{ then } i = \mu '(i)
$$
$$
\begin{cases}
M_{ i } , &\text{ unmatched under } \mu \text{ and } \mu ' \\
W_{ i } , &\text{ }  \\ 
\end{cases} 
$$
is indifferent between $$ \mu  $$ and $$ \mu ' $$ 

### Case 2:
$$
\text{ case 2. } \text{ If } \mu (i) != i \\
\text{ and } \mu (i)\sim_{ i } \mu '(i),\\
\text{ then } \mu (i) = \mu (i)'
$$
Moreover,
$$
\mu (\mu (i)) \sim_{ \mu (i) = \mu '(i) } \mu '(\mu (i))=i 
$$

### Case 3:
$$ \mu (i) \neq i $$ and i is not indifferent between $$\text{ and } \mu ' $$ , 
Claim: If all firms in case 3, prefer $$ \mu ' $$ to $$ \mu $$, then all workers prefer $$ \mu  $$ to $$ \mu ' $$ .
$$
\mu (F_{ 3 } )=W_{ 3 }  
$$
.

Know 
$$
\mu ' (f) \gt _{ f } \mu (f) \text{ for all }  f \in F_{ 3 } .
$$

Then, it must be the case that
$$
\mu(\mu '(f)) \gt_{ \mu '(f)} \mu '(\mu '(f)) = f 
$$
Otherwise, there exists some $$ f \text{ s.t. }  $$ 
$$
\mu \left( \mu '(f) \right) \lt _{ \mu '(f) } f 
$$

$$ (f,\mu '(f)) $$ is a blocking pair for $$ \mu $$, contradiction.

## Preposition 6:
No stable matching mechanims exists for which stating the true preferences is a dominant strategy for every agent.

## Proposition 7
With a mechanism that yields the F-optimal stable matching, it is a modimant stategy for each firm ...

$$
m_{ 1 } : w_{ 1 } \:w_{ 2 } \:m_{ 1 } \\
m_{ 2 } : w_{ 2 } \:w_{ 1 } \:m_{ 2 } \\
w_{ 1 } : m_{ 2 } \:m_{ 1 } \:w_{ 1 } \\
w_{ 2 } : m_{ 1 } \:m_{ 2 } \:w_{ 2 } \\
$$

$$
\mu ^{ m }        \\
m_{ 1 } - w_{ 1 } \\
m_{ 2 } - w_{ 2 } \\
\mu ^{ w }        \\
m_{ 1 } - w_{ 2 } \\
m_{ 2 } - w_{ 1 } \\
$$





