<h3>Experiment 22 (Efficientnet_b0):</h3>
<p> Notes: Padding instead of resize, mean std dev. values for normalization calc globally, training interrupted prematurely</p>
<p>
P: Model MSE = 969.3774, Baseline MSE = 956.1005, Normalized = 1.0139<br>
K: Model MSE = 3404.8650, Baseline MSE = 3448.3214, Normalized = 0.9874 <br>
Mg: Model MSE = 1470.4374, Baseline MSE = 1448.3911, Normalized = 1.0152<br>
pH: Model MSE = 0.0661, Baseline MSE = 0.0677, Normalized = 0.9765<br>
</p>
<ul>
    <li>1x1 conv with 3 filters</li>
    <li>different hyperparameters (smaller lr)</li>
    <li>efficientnet_b0, pretrained = True</li>
    <li>augmentations for training:
        <ul>
            <li>v2.RandomHorizontalFlip(p=0.5),</li>
            <li>v2.GaussianNoise(mean=0.0, sigma=0.03)</li>
        </ul>
    </li>
</ul>


<h3>Experiment 23 (Efficientnet_b0):</h3>
<p> Notes: Padding instead of resize, mean std dev. values for normalization calc globally</p>
<p>
P: Model MSE = 962.8198, Baseline MSE = 956.1005, Normalized = 1.0070<br>
K: Model MSE = 3423.0977, Baseline MSE = 3448.3214, Normalized = 0.9927<br>
Mg: Model MSE = 1480.3582, Baseline MSE = 1448.3911, Normalized = 1.0221<br>
pH: Model MSE = 0.0671, Baseline MSE = 0.0677, Normalized = 0.9917<br>
</p>
<ul>
    <li>1x1 conv with 10 filters</li>
    <li>different hyperparameters (smaller lr)</li>
    <li>efficientnet_b0, pretrained = False</li>
    <li>augmentations for training:
        <ul>
            <li>v2.RandomHorizontalFlip(p=0.5),</li>
            <li>v2.GaussianNoise(mean=0.0, sigma=0.03)</li>
        </ul>
    </li>
</ul>

<h3>Experiment 24 (Efficientnet_b0):</h3>
<p> Notes: Padding instead of resize, mean std dev. values for normalization calc globally</p>
<p>
P: Model MSE = 990.8983, Baseline MSE = 956.1005, Normalized = 1.0364<br>
K: Model MSE = 5301.6675, Baseline MSE = 3448.3214, Normalized = 1.5375<br>
Mg: Model MSE = 1577.3319, Baseline MSE = 1448.3911, Normalized = 1.0890<br>
pH: Model MSE = 0.0746, Baseline MSE = 0.0677, Normalized = 1.1031<br>
</p>
<ul>
    <li>1x1 conv with 15 filters</li>
    <li>different hyperparameters (smaller lr)</li>
    <li>efficientnet_b0, pretrained = False</li>
    <li>augmentations for training:
        <ul>
            <li>v2.RandomHorizontalFlip(p=0.5),</li>
            <li>v2.GaussianNoise(mean=0.0, sigma=0.03)</li>
        </ul>
    </li>
</ul>

<h3>Experiment 25 (convnext_base_in22k):</h3>
<p> Notes: Decreasing val loss and training loss (learning curves), padding instead of resize, mean std dev. values for normalization calc globally, changed hyperparameters</p>
<p>
P: Model MSE = 965.4764, Baseline MSE = 956.1005, Normalized = 1.0098<br>
K: Model MSE = 3227.5916, Baseline MSE = 3448.3214, Normalized = 0.9360<br>
Mg: Model MSE = 1480.8820, Baseline MSE = 1448.3911, Normalized = 1.0224<br>
pH: Model MSE = 0.0630, Baseline MSE = 0.0677, Normalized = 0.9312<br>
</p>
<ul>
    <li>1x1 conv with 3 filters</li>
    <li>different hyperparameters (smaller lr)</li>
    <li>convnext_base_in22k, pretrained = True</li>
    <li>augmentations for training:
        <ul>
            <li>v2.RandomHorizontalFlip(p=0.5),</li>
            <li>v2.GaussianNoise(mean=0.0, sigma=0.03)</li>
        </ul>
    </li>
</ul>

<h3>Experiment 26 (convnext_base_in22k):</h3>
<p> Notes: Decreasing val loss and training loss (learning curves), padding instead of resize, mean std dev. values for normalization calc globally, changed hyperparameters</p>
<p>
P: Model MSE = 961.5493, Baseline MSE = 956.1005, Normalized = 1.0057 <br>
K: Model MSE = 3242.3088, Baseline MSE = 3448.3214, Normalized = 0.9403 <br>
Mg: Model MSE = 1424.8456, Baseline MSE = 1448.3911, Normalized = 0.9837 <br>
pH: Model MSE = 0.0608, Baseline MSE = 0.0677, Normalized = 0.8980 <br>
</p>
<ul>
    <li>1x1 conv with 3 filters</li>
    <li>different hyperparameters (higher lr, batch 32 -> 64)</li>
    <li>convnext_base_in22k, pretrained = True</li>
    <li>augmentations for training:
        <ul>
            <li>v2.RandomHorizontalFlip(p=0.5),</li>
            <li>v2.GaussianNoise(mean=0.0, sigma=0.03)</li>
        </ul>
    </li>
</ul>
