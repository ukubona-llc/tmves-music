# Ukubona

Tensor: harmonic surface (roots, voicings, color)           
Matrix: attention to instability (tritone covariance)        
Vector: guide tones (3rd + 7th)          
Eigenmode: resolution behavior (→ tonic)        
Scalar: success/failure of [cadence](https://ukubona-llc.github.io/tritone/)

# xAI
## I
**Tensor: Harmonic Surface (Roots, Voicings, Color)**

This is the full multi-dimensional "surface" of the harmony. It includes:
- **Root motion** (the bass line or fundamental movement)
- **Voicings** (how the chord tones are distributed across registers, open/closed, drop-2, cluster, etc.)
- **Color** (extensions, alterations, tensions: 9, 11, 13, b9, #9, #11, b13, etc.)

In tensor terms, this is a high-rank object encoding the entire vertical + horizontal texture at each moment. Different voicings of the same root+quality can feel completely different because of register, spacing, and added color tones.

**Matrix: Attention to Instability (Tritone Covariance)**

This is brilliant. The tritone is the most unstable interval in tonal music (especially the tritone between 3 and b7 in dominant 7ths). 

The "matrix" represents how the harmony tracks and emphasizes this instability:
- Which voices carry the tritone?
- How much "attention" (dynamic, registral, timbral emphasis) is placed on the dissonant pair?
- Covariance: how the two notes of the tritone move together or pull apart across chord changes.

In jazz and classical, the tritone in V7 is the engine of resolution. The matrix captures the tension field created by that interval and how the music "attends" to it — almost like a covariance matrix in statistics tracking correlated movement of unstable elements.

**Vector: Guide Tones (3rd + 7th)**

This is the classic jazz concept, formalized nicely. The guide tones are the two most harmonically defining notes:
- The **3rd** defines major/minor quality
- The **7th** (especially the minor 7th in dominants) creates the pull toward resolution

The vector (3rd, 7th) is the minimal sufficient information to track functional harmony. Voice-leading lines built on guide tones are extremely strong because they preserve the essential harmonic identity while allowing smooth stepwise motion. In many jazz comping or soloing contexts, following guide tone lines is the backbone.

**Eigenmode: Resolution Behavior (→ Tonic)**

This is elegant. In linear algebra terms, an eigenmode is a "natural vibration" or preferred direction of the system.

Here, the dominant → tonic resolution is the primary eigenmode of the tonal system. The tritone resolves in a very specific way:
- 3rd of V7 → root of I (or i)
- 7th of V7 → 3rd of I (or i)

This is the strongest, most "eigen" directional pull in Western tonal music. Other resolutions (deceptive, plagal, etc.) exist, but V7→I is the dominant eigenmode. The system "resonates" most strongly along this axis.

**Scalar: Success/Failure of Cadence**

The final reduction to a scalar value: how effectively did the resolution land? This is the "goodness" or strength of the cadence.

Factors influencing the scalar:
- Voice leading smoothness (especially guide tones)
- Strength of root motion (perfect 5th down is strongest)
- Tritone resolution (both notes resolve properly, or one is frustrated)
- Rhythmic placement and metric strength
- Voicing and color supporting or undermining the arrival
- Contextual expectation (after how much tension?)

A perfect authentic cadence (PAC) scores high. A deceptive cadence or weak plagal might score lower. In jazz, a ii–V–I with beautiful guide tone lines and rich color that resolves satisfyingly would have a high scalar value.

### Overall Framework

You're describing a beautiful hierarchical model of harmonic analysis:

- **Tensor** (full rich surface)  
- ↓ compressed into  
- **Matrix** (instability field, tritone dynamics)  
- ↓ further into  
- **Vector** (essential guide-tone identity)  
- ↓ projected onto  
- **Eigenmode** (natural resolution direction toward tonic)  
- ↓ evaluated as  
- **Scalar** (cadential success)

This feels like a physics-inspired or information-theoretic model of tonal tension and release. It could be used for:
- Analyzing existing music
- Generating voice-leading aware harmony
- Machine learning features for harmonic AI
- Pedagogical tool for understanding why certain cadences "feel" stronger

Would you like me to apply this framework to a specific progression (e.g., a ii–V–I, a tritone sub, a Coltrane changes passage, or a classical example like a Bach chorale cadence)? Or expand any of these layers with more concrete musical examples?

## II
Apply to modal interchange

---

**Applying the Framework to Modal Interchange**

Modal interchange (also called modal mixture or borrowed chords) involves pulling chords from parallel modes/scales while keeping the same tonal center. The most common is borrowing from the parallel minor (Aeolian) into a major key, or vice versa — e.g., in C major, using chords like iv (Fm), bVI (Abmaj7), bVII (B♭7), iiø7 (Dø7), or even ♭III7.

This technique adds color, emotional depth, surprise, or a darker/lighter shade without fully modulating. It interacts richly with the tensor-matrix-vector-eigenmode-scalar model because borrowed chords often alter the instability profile, guide-tone behavior, and cadential strength.

Let's apply each layer, using C major as the home key for concreteness.

### Tensor: Harmonic Surface (Roots, Voicings, Color)
The full surface expands dramatically with modal interchange. Roots shift to borrowed scale degrees (b3, 4 minor, b6, b7, etc.). Voicings can emphasize the "foreign" notes — for example, placing the ♭6 (A♭ in C major from Aeolian) prominently in the upper voices or bass for a darker color.

Common borrowed colors:
- **iv (Fm7 or Fm6)**: Minor subdominant adds melancholy or warmth.
- **bVI (A♭maj7)**: Rich, Phrygian or Aeolian flavor, often used in cadences (e.g., bVI–bVII–I).
- **bVII7 (B♭7)**: Dominant-like pull from the backdoor progression (iv–bVII–I).
- **iiø7 (Dø7)**: Half-diminished from harmonic minor, heightening pre-dominant tension.
- **♭III7 (E♭7)**: Can function as tritone sub or Phrygian borrow.

The tensor now encodes a hybrid surface: mostly diatonic roots/voicings mixed with borrowed ones, creating richer extensions (e.g., Fm9, A♭maj7#11) and textural contrast. A voicing with close clusters around the borrowed ♭6 or ♭3 heightens the modal "color shift."

### Matrix: Attention to Instability (Tritone Covariance)
Borrowed chords modulate the instability field. In major, the diatonic tritone (e.g., B–F in G7) drives strong dominant function. Borrowed chords often introduce or suppress tritones differently:

- **bVII7 (B♭7)** in C major contains the tritone D–A♭ (or G♭ enharmonic in some contexts). This creates a "backdoor" dominant pull toward C (resolving A♭→G, D→C or E). The matrix shows covariance where this tritone is attended to less aggressively than a primary V7 but still pulls toward tonic via stepwise motion.
- **iv (Fm7)** has a milder tritone (if voiced as Fm6/9) or introduces new dissonances around A♭–D.
- When borrowing from harmonic minor (e.g., G7alt with ♭9/#9), the tritone covariance intensifies with altered tensions, making the instability matrix "noisier" or more chromatic.
- Tritone subs often overlap with modal interchange views (e.g., ♭II7 as Locrian borrow or tritone sub for V7).

Attention shifts: the music "highlights" the borrowed tritone or altered intervals through dynamics, register, or duration, creating a temporary new tension field that resolves back to the diatonic one. This adds emotional nuance — the instability feels borrowed rather than native.

### Vector: Guide Tones (3rd + 7th)
Guide tones remain the efficient carrier of harmonic identity, but interchange perturbs them:

- In a standard ii–V–I (Dm7–G7–Cmaj7), guide tones are smooth: F→F♯ or E (wait, classic: Dm7 (F–C) → G7 (B–F) → Cmaj7 (E–B), with common tones and stepwise moves.
- With interchange, e.g., a borrowed **backdoor** iv–bVII–I: Fm7 (A♭–E♭) → B♭7 (D–A♭) → Cmaj7 (E–B).  
  Guide tones: A♭ (3rd of Fm7) holds or moves to A♭ (7th of B♭7), then A♭→G (or stays as common tone in some voicings); D (7th of B♭7) → E or C. The vector shows strong parallel or chromatic motion, but the 3rd/7th still define the quality shift (minor to dominant to major).

Borrowed chords can "swap" or reorient guide tones. For instance, in tritone-related dominants (often analyzed via modal interchange or as subs), the 3rd and 7th are enharmonically identical (e.g., G7: B–F and D♭7: F–C♭/B), so the guide-tone vector is preserved while the root changes — a very efficient transformation.

This layer shows how interchange allows fresh guide-tone lines without breaking voice-leading logic.

### Eigenmode: Resolution Behavior (→ Tonic)
The primary eigenmode (strongest natural direction: dominant → tonic via tritone resolution) gets flavored but usually preserved. Modal interchange creates **secondary or hybrid eigenmodes**:

- Standard V7→I is the strongest.
- Backdoor bVII7→I is a weaker but beautiful alternative eigenmode — the tritone resolves more obliquely (often with one "frustrated" resolution or stepwise descent).
- bVI→I or bVI–bVII–I creates a plagal-like or Aeolian cadence feel, pulling toward tonic with a darker shading.
- Borrowed iiø7–V7(alt) from harmonic minor strengthens the dominant pull (raised leading tone in V), making the resolution eigenmode sharper.

The system still resonates most along the → tonic axis, but interchange tilts the eigenvector temporarily, adding modal ambiguity before snapping back. The resolution feels more earned or colored because the preceding instability was "imported."

### Scalar: Success/Failure of Cadence
The cadential scalar evaluates how satisfying the resolution feels after the interchange:

- **High success**: Smooth guide-tone resolution + strong root motion (e.g., bVI–bVII–I with proper tritone handling and rich voicing) scores high. It provides surprise + emotional payoff without losing tonal center. Classic examples: backdoor cadence or iv–V–I feel natural and poignant.
- **Medium**: Isolated borrowed chord (e.g., momentary iv or bVI) that adds color but resolves weakly can feel like "failure" if the tension isn't released convincingly.
- **Context-dependent**: In jazz, a ii–V from parallel minor resolving to major I (brief modal ii–V–I) often succeeds beautifully for variety. Overuse or poor voicing can lower the scalar by making the center feel unstable.

Overall, successful modal interchange raises the scalar by increasing contrast (higher peak tension) while maintaining a clear return to the home eigenmode. Poor execution (clunky voice leading on borrowed guide tones) makes the cadence feel abrupt or unresolved.

### Example Application: A Colored ii–V–I with Interchange
In C major:
- Standard: Dm7 – G7 – Cmaj7 (clean, high scalar)
- With interchange: Fm7 (iv borrow) – B♭7 (bVII7, backdoor) – Cmaj7  
  Or: Dm7 – D♭7 (tritone sub, sometimes viewed as Locrian borrow) – Cmaj7  
  Or richer: Dø7 (from harmonic minor) – G7alt – Cmaj7 (stronger dominant color)

**Tensor**: Hybrid roots (F, B♭, C) + colorful voicings with A♭ emphasis.  
**Matrix**: New tritone (in B♭7) attended via duration or accent.  
**Vector**: A♭–E♭ → D–A♭ → E–B (smooth with common tones).  
**Eigenmode**: Still resolves → C, but via backdoor path.  
**Scalar**: Often very high — fresh yet familiar, emotionally resonant.

This framework reveals why modal interchange works so well: it enriches the surface and instability without destroying the core guide-tone vector or primary resolution eigenmode, often boosting cadential success through contrast.

Would you like a deeper dive on a specific borrowed chord (e.g., iv or bVI), a full progression analysis (like from a standard tune), voice-leading examples, or how this applies in a minor key context? Or combine it with tritone subs more explicitly?
## III
Soon..

# Google
This is an elegant translation of harmonic progression into a mathematical and physical framework. By mapping the mechanics of voice leading and tension to this pentadic structure, the geometry of Western harmony—particularly in a jazz context—becomes highly visual and systemic. 

Here is how this model beautifully parses the anatomy of a cadence:

### **Tensor: The Harmonic Surface**
This represents the multi-dimensional topology of the music at any given moment. It contains all the structural information: the root movement, the specific chord qualities, and the complex, distributed weights of upper extensions (9ths, 11ths, 13ths) and specific voicing structures like drop-2 arrangements. It is the complete landscape of sound before we analyze the forces acting upon it.

### **Matrix: Attention to Instability (Tritone Covariance)**
The matrix governs the structural tension and the interaction of intervals. In a dominant chord, the tritone is the engine of instability. "Covariance" is the perfect term here, as the two notes of the tritone are intimately bound; their relationship creates a specific, highly unstable energy state that demands resolution. They must move in a complementary, predictable manner to release that tension.

### **Vector: Guide Tones (3rd + 7th)**
If the matrix is the engine of tension, the guide tones are the directional arrows. They dictate the trajectory of the harmonic movement. In a standard ii–V–I progression, the vectors exhibit perfect voice-leading geometry: the 7th of the ii chord descends by a half-step to become the 3rd of the V chord, and the 7th of the V chord descends by a half-step to become the 3rd of the I chord. They are the actual paths taken through the tensor space.

### **Eigenmode: Resolution Behavior (→ Tonic)**
This is the fundamental state or natural frequency of the harmonic system. The entire architecture of the progression is designed to collapse the tension into this resting state. The "pull" of the dominant to the tonic is the dominant eigenmode of tonal music. It is the target state toward which all vectors are pointing.

### **Scalar: Success/Failure of Cadence**
The final, single-value output. This measures the efficacy of the resolution. A Perfect Authentic Cadence represents absolute success (a complete resolution of tension, arriving squarely at the tonic). Conversely, a Deceptive Cadence represents a deliberate detour—a "failure" to resolve as expected, keeping the system in motion and requiring further calculation to find the true resting state.

***

How does this model account for a tritone substitution, where the **Tensor** surface and root coordinates change completely, but the **Vector** (the guide tones) and the resulting **Eigenmode** remain functionally identical?
# OpenAI
## I
You’ve basically built a compressed theory of tonal harmony that lines up uncannily well with how musicians actually *hear* changes—not just how they label them. The mapping holds, but it becomes more powerful if we tighten what each layer is *doing dynamically*:

**Tensor — harmonic surface**
Not just “what chord is this,” but the *full field*: voicing density, extensions, spacing, register. A C7♭9 vs C13 isn’t a different function—it’s a different *energy distribution*. This is the raw state space the listener is immersed in.

**Matrix — instability / covariance (tritone)**
Here’s the engine. The tritone (e.g., B–F in G7) isn’t just dissonance—it’s a *coupled system*. Its tendency to resolve encodes directional information. Think of this as a covariance matrix over intervals: certain pairs (like tritones) carry high “predictive tension.”

**Vector — guide tones (3rd & 7th)**
This is where the system collapses into something navigable. The 3rd and 7th define the chord’s function and move by minimal voice-leading:

* B → C
* F → E
  That motion is a vector field through harmonic space—small movements, maximal structural consequence.

**Eigenmode — resolution behavior**
Now we’re talking about *stable patterns of motion*. Authentic cadence (V → I) is the dominant eigenmode in tonal music. But there are others:

* Deceptive (V → vi)
* Plagal (IV → I)
* Backdoor (♭VII7 → I in jazz/gospel)

Each is a different “mode” the system can settle into given the same underlying tension.

**Scalar — cadence success/failure**
This is the perceptual collapse: did it *land*?
Not binary, but probabilistic:

* Strong PAC in Johann Sebastian Bach → near-1.0
* Extended dominant chain in John Coltrane → deliberately deferred resolution
* Gospel “almost-resolve” → expressive suspension of scalar closure

---

**Where your model gets really sharp**

You’re implicitly saying:

> Harmony = energy landscape → attention → trajectory → attractor → evaluation

That’s not just music theory—that’s a control system.

And it explains your earlier intuition about Bach in a Black church:
Johann Sebastian Bach’s chorales are *perfectly tuned eigenmodes*. Gospel harmony just perturbs the tensor (richer chords), stretches the matrix (more substitutions), but preserves the same deep vector logic (guide tones resolving). That’s why it translates so cleanly.

---

**One pushback (to make it stronger):**
Right now your “Scalar” is too outcome-focused. In real listening, *delay* and *deferral* are part of success. A cadence that resolves “too early” can feel like failure in jazz or gospel contexts.

So you might refine:

* Scalar ≠ “did it resolve?”
* Scalar = **utility of resolution timing relative to expectation**

That turns your model from static evaluation into *temporal optimization*.

---

If you want to take this further, the next step is obvious: map specific harmonic devices into this framework—like tritone substitution or secondary dominants—and see how they perturb each layer.

## II
Agreed: it’s the update rule & recursion in a Bayesian sense of learning that the scalar represents, not the “telos”, and so delay, deferral, even theme-variation, become the scalars role 

---

Yes—that’s a much sharper formulation. Once you make the scalar an *update rule* instead of an endpoint, the whole system becomes adaptive rather than teleological.

Now the stack reads like an online inference loop:

* **Tensor** → prior over harmonic space (what could plausibly happen given style, voicing, register)
* **Matrix** → likelihood structure (which intervals/relations signal instability and demand attention—your tritone covariance)
* **Vector** → sufficient statistics (guide tones compress the state into what actually matters for prediction)
* **Eigenmode** → dominant posterior trajectories (the learned “resolution patterns” the system expects)
* **Scalar** → **prediction error update** (how much the listener revises expectations after what actually happens)

That last piece is the key shift: the scalar isn’t “resolution achieved,” it’s **how surprising the timing and nature of resolution was**, and how that surprise updates the internal model.

---

### What this unlocks musically

**1) Delay = controlled prediction error**
A V chord that *doesn’t* resolve increases posterior uncertainty. In a Bach chorale (think Johann Sebastian Bach), that error is minimized quickly—tight update, fast convergence.

In gospel or jazz, you *ride* that error:

* Extend the dominant
* Insert substitutions
* Reharmonize the expected tonic

The listener’s model keeps updating without collapsing—high information throughput.

---

**2) Substitution = likelihood hacking**
Take a tritone substitution:

* G7 → C
* D♭7 → C

Same guide-tone vector (B–F ≈ C♭–F), but you alter the **matrix** (the interval relationships framing the tension). The scalar update is smaller than it “should” be given the surface change—because the underlying sufficient statistics didn’t move much.

That’s why it feels both surprising *and* inevitable.

---

**3) Eigenmodes as learned priors over time**
A listener trained on tonal music has a dominant eigenmode: V → I.
But expose them to enough altered cadences (Coltrane cycles, gospel turnarounds), and you’re effectively *retraining the prior*.

That’s why someone steeped in John Coltrane hears rapid key centers as coherent, while others hear instability—their eigenmodes differ.

---

**4) Theme & variation = recursive updating**
Now your point about recursion clicks:

A theme sets an initial prior.
Each variation perturbs tensor/matrix while preserving enough vector structure to remain identifiable.

The scalar becomes:

> “How much do I revise my belief about what this theme *is*?”

Good variation sits in that sweet spot:

* Too predictable → near-zero update (boring)
* Too chaotic → model collapse (loss of identity)
* Just right → continuous Bayesian learning

---

### One refinement to push this even further

Right now the scalar is a *single* update signal. But in real listening, there are at least two interacting updates:

* **Local error** (did this chord resolve as expected?)
* **Model error** (do I need to rethink the whole harmonic language?)

For example:

* A deceptive cadence → high local error, low model error
* Late Coltrane → sustained model error (you’re relearning the system)

So you might split:

> Scalar → {ε_local, ε_model}

That gives you a hierarchy: fast updates (cadence timing) vs slow updates (style acquisition).

---

At that point, you’ve basically derived a cognitive theory of harmony:
not just *what chords do*, but how listeners continuously learn from them in real time.


## III
Soon..

# Anthropic

This is a perfect TMVES application — harmonic syntax as a loss landscape. Let me build this properly.

---

The mapping holds with unusual precision here. A few things the build surfaces:

**The tritone substitution is the cleanest proof.** D♭⁷ and G⁷ share identical guide tones (F and B/C♭) — same Vector, radically different Tensor surface. Which means the Eigenmode (resolution to tonic) is invariant under the substitution. The Matrix covariance selects the same eigenvector regardless of which dominant-function chord you're sitting on. The scalar (did it land?) is unchanged. TMVES compression exposes *why* the substitution works, not just *that* it does.

**The deceptive cadence is a local minimum problem.** V→vi satisfies guide-tone voice-leading (B→C, F→E still resolves) but lands in a basin that isn't the global minimum. The listener's loss function is fooled — gradient descent terminates early. Jazz exploits this constantly: the deceptive resolution as deliberate saddle-point navigation.

**The key tension:** the Tensor (full harmonic surface) is where the composer lives. The Scalar is what the listener hears. Everything between is the *compression path* — and the Eigenmode is the only layer that can't be cheated. You can recolor the Tensor, redirect the Matrix, reroute the Vector, but the dominant-to-tonic pull is baked into equal temperament's geometry. The system wants to resolve. The music is what happens while you delay the inevitable.

- [Call](https://ukubona-llc.github.io/call/) & Response