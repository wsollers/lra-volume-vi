# Volume VI - Algebra Proofs To Do

Proof-writing order is dependency-first among active proof labels. Dependency edges come from resolved statement and proof dependency blocks; original source order is the stable tie-breaker.
Use `✅` to record completion after the canonical proof file has both proof bodies populated and validated.

Open proofs to do: 46
Completed in this tracker: 0
Unresolved dependency edges skipped for ordering: 1
Duplicate proof labels skipped: 7

1. () `thm:hilbert-basis-theorem` — **Hilbert Basis Theorem**
   > **Statement.**
   > If $R$ is a Noetherian ring, then the polynomial ring $R[x]$
   > is also Noetherian.
   >
   > In particular, $k[x_1, \dots, x_n]$ is Noetherian for any field $k$.

2. () `prop:abstract-domain-cancellation` — **Cancellation in Integral Domains**
   > **Statement.**
   > Let $R$ be an integral domain.  If $a\neq 0$ and $ab=ac$, then $b=c$.

3. () `prop:abstract-field-is-domain` — **Every Field is an Integral Domain**
   > **Statement.**
   > Every field is an integral domain.

4. () `prop:identity-element-unique` — **Uniqueness of the Identity**
   > **Statement.**
   > In a group, the identity element is unique.

5. () `prop:inverse-element-unique` — **Uniqueness of Inverses**
   > **Statement.**
   > In a group, every element has a unique inverse.

6. () `prop:field-characteristic` — **Characteristic of a Field**
   > **Statement.**
   > Let $\mathbb{F}$ be a field. The \emph{characteristic} of $\mathbb{F}$
   > is the smallest positive integer $n$ such that
   > \[
   > \underbrace{1 + 1 + \cdots + 1}_{n} = 0,
   > \]
   > or $0$ if no such $n$ exists.
   > The characteristic of a field is either $0$ or a prime $p$.

7. () `prop:field-inverse-exists` — **Nonzero Scalars Have Inverses**
   > **Statement.**
   > Let $\mathbb{F}$ be a field and $a \in \mathbb{F}$ with $a \neq 0$.
   > Then there exists a unique $a^{-1} \in \mathbb{F}$ such that
   > $a \cdot a^{-1} = 1$.

8. () `prop:field-is-domain` — **Every Field is an Integral Domain**
   > **Statement.**
   > Every field is an integral domain.

9. () `prop:field-zero-product` — **Zero Product Property in a Field**
   > **Statement.**
   > Let $\mathbb{F}$ be a field and $a, b \in \mathbb{F}$. Then
   > \[
   > ab = 0 \;\Longrightarrow\; a = 0 \;\text{ or }\; b = 0.
   > \]

10. () `prop:group-cancellation-in-groups` — **Cancellation Laws**
   > **Statement.**
   > Let $G$ be a group and let $a, b, c \in G$. Then:
   > \begin{enumerate}[label=(\roman*)]
   >   \item \textbf{Left cancellation:} $ab = ac \implies b = c$.
   >   \item \textbf{Right cancellation:} $ba = ca \implies b = c$.
   > \end{enumerate}

11. () `prop:group-identity-unique` — **Uniqueness of the Identity**
   > **Statement.**
   > Let $G$ be a group. The identity element of $G$ is unique.

12. () `prop:group-inverse-unique` — **Uniqueness of Inverses**
   > **Statement.**
   > Let $G$ be a group. For each $a \in G$, the inverse of $a$ is unique.

13. () `prop:group-socks-shoes` — **Socks-Shoes Property**
   > **Statement.**
   > Let $G$ be a group and let $a, b \in G$. Then
   > \[
   > (ab)^{-1} = b^{-1} a^{-1}.
   > \]

14. () `prop:group-cancellation` — **Cancellation Laws in a Group**
   > **Statement.**
   > Let $G$ be a group and let $a,b,c \in G$.
   > If $ab = ac$, then $b=c$.
   > If $ba = ca$, then $b=c$.

15. () `prop:absorbing-unique` — **Uniqueness of the Absorbing Element**
   > **Statement.**
   > A two-sided absorbing element, if it exists, is unique.

16. () `prop:domain-cancellation` — **Cancellation in Integral Domains**
   > **Statement.**
   > In an integral domain, if $a\neq 0$ and $ab=ac$, then $b=c$.

17. () `prop:finite-domain-is-field` — **Finite Integral Domain is a Field**
   > **Statement.**
   > Every finite integral domain is a field.

18. () `thm:general-associativity` — **General Associativity**
   > **Statement.**
   > If $\star$ is associative, then any finite product
   > $a_1\star a_2\star\cdots\star a_n$ has a value independent of
   > parenthesization.

19. () `prop:identity-collapse` — **Identity Collapse and Uniqueness**
   > **Statement.**
   > If $\star$ has a left identity $e_L$ and a right identity $e_R$, then
   > $e_L=e_R$. Consequently a two-sided identity, if it exists, is unique.

20. () `prop:inverse-collapse` — **Inverse Collapse and Uniqueness in a Monoid**
   > **Statement.**
   > If $\star$ is associative with identity $e$, and $a$ has a left inverse $b$
   > and a right inverse $c$, then $b=c$. Hence the inverse of an invertible
   > element is unique.

21. () `prop:invertible-implies-cancellable` — **Invertible Implies Cancellable**
   > **Statement.**
   > In a monoid, every invertible element is cancellable.

22. () `prop:ring-mult-neg` — **Multiplication by Additive Inverse**
   > **Statement.**
   > In a ring, $a\cdot(-b)=-(a\cdot b)=(-a)\cdot b$. In a ring,
   > $(-1)\cdot a=-a$.

23. () `prop:ring-mult-zero` — **Multiplication by Zero**
   > **Statement.**
   > In a ring, $a\cdot 0=0\cdot a=0$ for all $a$.

24. () `prop:socks-shoes` — **Socks--Shoes**
   > **Statement.**
   > In a group, $(ab)^{-1}=b^{-1}a^{-1}$.

25. () `prop:units-form-group` — **Units of a Monoid Form a Group**
   > **Statement.**
   > In a monoid $(A,\star,e)$, the set $A^\times$ of invertible elements is
   > closed under $\star$ and forms a group.

26. () `prop:boolean-ring-commutativity-from-idempotence` — **Commutativity from Idempotence**
   > **Statement.**
   > In any Boolean ring $R$,
   > \[
   >   pq=qp \quad \text{for all } p,q\in R.
   > \]
   > Hence every Boolean ring is a commutative ring.

27. () `cor:boolean-ring-finite-order-power-two` — **Order is a Power of Two**
   > **Statement.**
   > A finite Boolean ring has order $2^n$ for some $n\geq 0$. In particular,
   > there is no Boolean ring of order $3$.

28. () `prop:boolean-ring-self-additive-inverse` — **Self Additive Inverse / Characteristic 2**
   > **Statement.**
   > In any Boolean ring $R$,
   > \[
   >   p+p=0 \quad \text{for every } p\in R.
   > \]

29. () `prop:boolean-ring-self-negation` — **Self Negation**
   > **Statement.**
   > In any Boolean ring $R$,
   > \[
   >   -p=p \quad \text{for every } p\in R.
   > \]

30. () `thm:stone-representation-boolean-rings` — **Stone Representation for Boolean Rings**
   > **Statement.**
   > Every Boolean ring is isomorphic to a field of sets. Every finite Boolean
   > ring is isomorphic to $\mathcal P(X)$ for some finite set $X$, hence has
   > $2^{|X|}$ elements.

31. () `prop:duality-principle` — **Duality Principle**
   > **Statement.**
   > Let $\Phi$ be a statement about partially ordered sets, expressed purely
   > in terms of $\leq$, that holds in every partially ordered set.  Then the
   > dual statement $\Phi^{\mathrm{op}}$, obtained by replacing every
   > occurrence of $\leq$ with $\geq$, also holds in every partially ordered
   > set.

32. () `prop:finite-poset-maximal` — **Every Nonempty Finite Poset Has a Maximal Element**
   > **Statement.**
   > Let $(P, \leq)$ be a finite partially ordered set.  Then every nonempty
   > subset $Q \subseteq P$ has at least one maximal element.  Furthermore,
   > for every $x \in P$ there exists $y \in \operatorname{Max}(P)$ with
   > $x \leq y$.

33. () `lem:order-embedding-injective` — **Every Order-Embedding Is Injective**
   > **Statement.**
   > Let $(P, \leq_P)$ and $(Q, \leq_Q)$ be partially ordered sets, and let
   > $\varphi : P \to Q$ be an order-embedding.  Then $\varphi$ is injective.

34. () `lem:order-iso-finite-characterizations` — **Characterizations of Order-Isomorphisms for Finite Posets**
   > **Statement.**
   > Let $(P, \leq_P)$ and $(Q, \leq_Q)$ be finite partially ordered sets and
   > let $\varphi : P \to Q$ be a bijection.  The following are equivalent:
   > \begin{enumerate}
   >   \item $\varphi$ is an order-isomorphism.
   >   \item For all $x, y \in P$:\; $x <_P y \;\Longleftrightarrow\; \varphi(x) <_Q \varphi(y)$.
   >   \item For all $x, y \in P$:\; $x \prec_P y \;\Longleftrightarrow\; \varphi(x) \prec_Q \varphi(y)$.
   > \end{enumerate}

35. () `prop:hasse-diagram-characterization` — **Hasse Diagram Characterization for Finite Posets**
   > **Statement.**
   > Let $(P, \leq_P)$ and $(Q, \leq_Q)$ be finite partially ordered sets.
   > Then $P$ and $Q$ are order-isomorphic if and only if their Hasse diagrams
   > are isomorphic as directed graphs --- that is, identical up to relabeling
   > of elements.

36. () `prop:predicates-power-sets-iso` — **Predicates and Power Sets Are Order-Isomorphic**
   > **Statement.**
   > The map $\Phi : (\mathcal{P}^*(X), \leq) \to (\mathcal{P}(X), \subseteq)$
   > is an \hyperref[def:order-isomorphism]{order-isomorphism}.

37. () `thm:addition-commutative-in-fn` — **Addition Is Commutative in $F^n$**
   > **Statement.**
   > For all $x,y \in \mathbf{F}^n$,
   > \[
   > x+y=y+x.
   > \]

38. () `thm:conditions-for-a-subspace` — **Conditions for a Subspace**
   > **Statement.**
   > Let $V$ be a vector space over $\mathbf{F}$ and let $U \subseteq V$.
   > Then $U$ is a subspace of $V$ if and only if the following three conditions hold:
   > \begin{enumerate}[label=(\roman*)]
   >   \item $0 \in U$;
   >   \item for all $u,v \in U$, one has $u+v \in U$;
   >   \item for all $a \in \mathbf{F}$ and all $u \in U$, one has $au \in U$.
   > \end{enumerate}

39. () `thm:sum-of-subspaces-smallest-containing` — **Sum of Subspaces Is the Smallest Containing Subspace**
   > **Statement.**
   > Let $V$ be a vector space over $\mathbf{F}$, and let
   > $U_1,\dots,U_m$ be subspaces of $V$.
   > Then $U_1+\cdots+U_m$ is a subspace of $V$ containing each of
   > $U_1,\dots,U_m$.
   > Moreover, if $W$ is a subspace of $V$ containing each of
   > $U_1,\dots,U_m$, then
   > \[
   > U_1+\cdots+U_m \subseteq W.
   > \]

40. () `thm:unique-additive-identity` — **Unique Additive Identity**
   > **Statement.**
   > A vector space has a unique additive identity.

41. () `thm:condition-for-direct-sum` — **Condition for a Direct Sum**
   > **Statement.**
   > Let $V$ be a vector space over $\mathbf{F}$, and let
   > $U_1,\dots,U_m$ be subspaces of $V$ such that
   > \[
   > V=U_1+\cdots+U_m.
   > \]
   > Then the following are equivalent:
   > \begin{enumerate}[label=(\roman*)]
   >   \item \(V=U_1\oplus\cdots\oplus U_m\);
   >   \item if \(u_1 \in U_1,\dots,u_m \in U_m\) and
   >         \[
   >         u_1+\cdots+u_m=0,
   >         \]
   >         then
   >         \[
   >         u_1=\cdots=u_m=0.
   >         \]
   > \end{enumerate}

42. () `thm:direct-sum-of-two-subspaces` — **Direct Sum of Two Subspaces**
   > **Statement.**
   > Let $U$ and $W$ be subspaces of a vector space $V$.
   > Then
   > \[
   > U+W=U\oplus W
   > \]
   > if and only if
   > \[
   > U \cap W = \{0\}.
   > \]

43. () `thm:unique-additive-inverse` — **Unique Additive Inverse**
   > **Statement.**
   > Every vector in a vector space has a unique additive inverse.

44. () `thm:scalar-times-zero-vector` — **$a0=0$**
   > **Statement.**
   > For every $a \in \mathbf{F}$,
   > \[
   > a0=0.
   > \]

45. () `thm:zero-scalar-times-vector` — **$0v=0$**
   > **Statement.**
   > For every $v \in V$,
   > \[
   > 0v=0.
   > \]

46. () `thm:minus-one-times-vector` — **$(-1)v=-v$**
   > **Statement.**
   > For every $v \in V$,
   > \[
   > (-1)v=-v.
   > \]
